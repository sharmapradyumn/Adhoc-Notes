# Day 13
``ansible localhost -m ping`` for same system
* `` ansible localhost -m command "date"``
* command module dodes not support ``|,>>``
* ``shell`` module understand everything
* ``ping`` module
* `` yum`` module
* `` ansible localhost -m service -a "name=httpd state=started"`` when we want to start services
* (yum,service,shell,copy)------->file---->its called playbook ------> language for it ``yaml``
* playbok have three section
1. Target(group)
2. Variable(optional)
3. Task (module)
4. start wit ``---``
5. give a space

# Modules
## Function
1. fxn with name
2. fxn without name(its called lambda)
* function ``def``
fxn 


``def hell() :
     print ()``
* Dynamic fxn
* ``def hell(x,y) :``its take only two input
* if wants to give input outside of fxn then import ``sys`` module
* ``print(sys.argv)`` will print inline input
* `` def hell(*x)``its take  the all input its a tuple
* 
