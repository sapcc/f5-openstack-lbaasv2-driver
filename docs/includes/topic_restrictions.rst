.. _f5-agent-unsupported-features:

Unsupported Features
--------------------

The following features are unsupported in |release|; they will be introduced in future releases.

* vCMP® (multi-tenancy)
* Agent High Availability
* BIG-IP® Device Service Clustering
* Multiple environments (Prod, Dev, Test)


.. note::

    The features supported in |release| are a subset of the `Neutron LBaaSv2 API <https://wiki.openstack.org/wiki/Neutron/LBaaS/API_2.0>`_ delivered in the OpenStack |openstack| release. The following restriction(s) apply:

    .. table::

        +----------------+----------------------------------------------------+
        | Object         | Unsupported                                        |
        +================+====================================================+
        | Loadbalancer   || Statistics                                        |
        |                || (e.g., ``neutron lbaas-loadbalancer-stats``)      |
        +----------------+----------------------------------------------------+
