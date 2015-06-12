.. _cloud_servers_product_concepts:

~~~~~~~~~~~~~~~~~~~~~~~~~~~
Understanding Cloud Servers
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Create one or many Cloud Servers to give yourself computing power in the
Rackspace managed cloud.

If you create a Cloud Server and decide that it doesn't meet your needs
(for example, if an application you want to install is not compatible
with the operating system), simply delete that Cloud Server and create a
different one.

You can create Cloud Servers of two types:

* virtual servers

* OnMetal™ servers

This is an architectural overview of virtual servers:

.. figure:: /_images/CloudServerVirtualArchitecture.png
   :alt: Virtual Cloud Servers are the core of a rich configuration.
   
   *Virtual cloud servers allow for configurations that handle 
   general-purpose workloads and highly optimized workloads. 
   In the configuration above, a web instance server pulls 
   data from the database. The server then communicates the data 
   to the web through a public network. 
   Dashed lines represent an optional branch of the configuration. 
   In this case, you have the option to add more servers if 
   needed to account for greater workloads.*

This is an architectural overview of OnMetal™ servers:

.. figure:: /_images/CloudServerOnMetalArchitecture.png
   :alt: OnMetal Cloud Servers add a performance boost.
   
   *OnMetal cloud servers are API-driven, which adds a performance boast. 
   They are highly optimized for specific workloads. 
   OnMetal Compute is optimized for high traffic web servers, 
   application servers, load balancers, and queue processing. 
   On Metal Memory is optimized for large scale caches, index searches, 
   and in-memory analytics. 
   OnMetal I/O is optimized for large relational databases 
   and Online Transaction Processing (OLTP) applications.*

Contents:

.. toctree::
   :maxdepth: 2

   create-server
   change-server
   flavor-class/index
   server-region
   metadata/index
   boot/index
   nova-agent
   SSH
   diskconfig
   host-issues
   time
   server-events