# ansible-redhatsatellite5to6migration
###### ansible wrapper around Red Hats bootstrap script which can be found in
###### the pub directory of Satellite 6.
###### Migration to new stand-alone Puppet environment, this is due to Puppets 
###### disappearance in version Satellite 7. Some logic to address different 
###### scenarios with multiple applications and databases.

###### some logic like getting installed application/db  can be replaced with 
###### other functions to extract info from a cmdb or other source depending on
###### your use case.
