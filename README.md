# puppetlabs puppetserver_gem module

This module provides management of Ruby gems for PuppetServer.


For PE Puppet Server:

    package { 'json':
      ensure   => present,
      provider => puppetserver_gem,
    }

This uses gem as a parent and uses the PE version of the
`puppetserver gem` command for all gem operations.
