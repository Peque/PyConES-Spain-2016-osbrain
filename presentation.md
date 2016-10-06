% DEVELOPING A REAL-TIME AUTOMATED TRADING PLATFORM WITH PYTHON
% Miguel Sánchez de León Peque
% 2016-10-08

# About

## Us

- [OpenSistemas](http://www.opensistemas.com)
- [www.opensistemas.com](http://www.opensistemas.com)
- R&D division
- [Fernando Monera Daroqui](https://www.linkedin.com/in/monera)
  fmonera@opensistemas.com

## Me

- [Miguel Sánchez de León Peque](https://www.linkedin.com/in/peque)
  msdeleon@opensistemas.com
- **Industrial engineer**
- Passion for **programming, data and ML**
- Met **Python** about 2 years ago

# Introduction

----

![Source: [Stanford CPU DB](http://cpudb.stanford.edu/)](./figures/clock_freq.png)

## Concurrency

- Locks
- Semaphores
- Critical sections

Code **fails**. Misterious bugs...

---

Irreversible disorders...

![](./figures/developers.gif){width=70%}

## Relativity

e = mc²

>- `e`: energy (effort)
>- `m`: mass (lines of code)
>- `c`: ~~speed of light~~ concurrency

----

![](./figures/scared.gif){width=100%}

## Multi-agent systems

- Autonomy of the agents
- Local views
- Decentralization

# osBrain

## Basics

> A **general purpose** multi-agent system

- Independent agents
- Message passing
- Easy configuration and deployment

## History

A real-time automated-trading platform

- Market data (fast, parallel)
- Isolation of strategies

## Processes vs. threads

Have you met GIL?

## ØMQ

- Higher level than raw sockets
- Asynchronous communication
- Multiconnetion (not necessarily one-to-one).
- Multipattern (REQ-REP, PUB-SUB...).
- Multitransport (inproc, ipc, tcp, pgm, epgm).
- Multilanguage (C, C++, Python, Scala, Haskell, Go...).
- Multiplatform.
- Scalable (threads, processes, machines)
- LGPL.

## Pyro4

- **PY**thon **R**emote **O**bjects
- Treat remote objects as local
- Has a name server implementation

----

![](./figures/osbrain-logo-name.svg){width=15cm}

- [https://pypi.python.org/pypi/osbrain](https://pypi.python.org/pypi/osbrain)
- [https://github.com/opensistemas-hub/osbrain](https://github.com/opensistemas-hub/osbrain)
- [https://pythonhosted.org/osbrain/](http://pythonhosted.org/osbrain/)

---

![](./figures/drink.gif){width=100%}

# Examples

---

TODO: link to examples repo

# The end

## References

- [osBrain source code](https://github.com/opensistemas-hub/osbrain)
- [osBrain documentation](http://pythonhosted.org/osbrain/)
- [ØMQ](http://zguide.zeromq.org/)
- [Pyro4](https://pythonhosted.org/Pyro4/)


## Contact

- [Miguel Sánchez de León Peque](https://www.linkedin.com/in/peque)
  *msdeleon@opensistemas.com*
- [Fernando Monera Daroqui](https://www.linkedin.com/in/monera)
*fmonera@opensistemas.com*
- [www.opensistemas.com](www.opensistemas.com)
- [robintradinghub.com](http://robintradinghub.com/)
- [blog.opensistemas.com](http://blog.opensistemas.com/)
- [twitter.com/opensistemas](https://twitter.com/opensistemas)

## We are hiring!

- [http://www.opensistemas.com/what-we-do/](http://www.opensistemas.com/what-we-do/)

```python
hired = [name for name, CV in candidates
         if CV in inbox('rrhh@opensistemas.com') and CV]
```

## Thank you!

- Questions?
- Comments?
- Suggestions?
