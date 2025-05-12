# Quickstart

!!! note
    **This guide is for CentOS/Fedora Linux distributions.**

    See mfext installation guide for adapt it for other distributions.


```console

$ ##### As root user #####

$ # We install the Python3 enabled version of python extra tools
$ yum -y install metwork-mfext-layer-python3_extratools


$ ##### As lambda user #####

$ # We load the mfext environment (if it is not already done)
$ . /opt/metwork-mfext/share/interactive_profile

$ # We check that the layer is installed and loaded
$ $ layers |grep extratools
- (*) python3_extratools@mfext [/opt/metwork-mfext/opt/python3_extratools]

$ # Let's test
$ python
>>> import jupyterlab
# [...] :-)
```
