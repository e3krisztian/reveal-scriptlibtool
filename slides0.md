#   Names for
# code fragments

### (based on reusability)

<br/>

<small>2013 October, @kr</small>



#### Code category
## Tool

- directly *executable*
- reusability supported by *parameters*
- *independent* of developer's machine
- *easily installable* with dependencies


### Is it a script, then?
### NO!

<p style="text-align: left">
    Usually the "script" you think of have
</p>

- *hard coded parameters* restricting the code to run only on the
   developer's machine
- *no machine readable* description of used libraries, dependencies



#### Code category
## Script

- performs a *concrete task*
- is directly *executable*
- has all its parameters *hard coded*
  <br />
  -> take *NO* user given parameters
- is *NOT reusable* by design


### Come on!
### I know from *experience*, that

- reuse is possible by *modifying* the script
- modification of scripts is the *most common* reuse of all

<br/>

#     ???


### Depending on
### code modification is
## <em style="color: red">strongly discouraged !</em>


### Why?

- code modification is inherently a manual work
- manual work directly translates to time:

    - where to modify?
    - what to modify?
    - test... test...
- would I be happy to take over the task of running someone else's scripts?


### Are scripts bad, then?
### NO!

<p style="text-align: left">
They
</p>

- are extremely useful building blocks
- are the easiest to create compared to other components
- can be quite easily "upgraded" to become *tools*:

    - hard coded parameters can be replaced with real parameters
    - a machine readable description of dependencies can be added



#### Code category
## Library

- *NOT executable*
- *pure reusable code*
- *invisible* for the user
- *solve hard problems* or provides *convenience*
- eliminates the need for code repetition
  <br />
  (in other words: minimalizes boilerplate)
- should be *tested* and *bug free*
- must be *known* to be used
- must have a good *documentation*, to be usable
- requires *patience and skill* to build
- thus, good libraries are very *valuable*



### How do different kinds
###  of codes work together?

<br />

- *scripts* are used exclusively by the end user.
- no code is allowed to reuse *scripts*.
- *libraries* can be used by any code.
- *tools* as *external processes* can be used by any code.



<section>
    ### Examples
    Script
    ...
    TBD
</section>



# THE END

<small>Created with reveal.js </small>
