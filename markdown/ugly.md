## The ugly


### The Drop
Pool performance declines with number of objects

Note: Explain how the number of objects insertable into a pool can
significantly degrade over time, as pools accumulate more and more
RADOS objects. 


### Directory Splits

Note: Explain the OSD filestore doing proactive directory splitting,
and how this can make inserts into a pool grind to a complete halt.


### Databases

Note: Explain how it’s a terrible idea to run databases in virtual
machines backed by Ceph, because databases usually want you to disable
any kind of database caching. 
