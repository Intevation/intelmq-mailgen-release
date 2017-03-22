# IntelMQ Mailgen Release

If a more complex contact database for sending out events via
email and other means is necessary, a combination of software components
can be used:

1. [IntelMQ](https://github.com/Intevation/intelmq/tree/integrated) from our integrated-branch
   An upstream [IntelMQ from the Cert-Tools](https://github.com/certtools/intelmq) repository will not work.
2. IntelMQ Manager
3. [IntelMQ Mailgen](https://github.com/intevation/intelmq-mailgen)
4. [Fody-API](https://github.com/intevation/intelmq-fody-api)
5. [Fody](https://github.com/intevation/intelmq-fody)

Our working label for the combination is __intelmq-cb-mailgen__.
The setup requires PostgreSQL.

Collection of stuff to manage releases of intelmq-cb-mailgen.  The
information which versions of intelmq, intelmq-mailgen,
intelmq-manager and further components form a specific release is
administered here.
