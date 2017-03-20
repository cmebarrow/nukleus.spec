# Nukleus Specification

- Defines the base control frames and streams frames which other nuklei must extend (see core.idl)
- Defines the control protocol (route and unroute commands) as k3po scripts 
- Control frames are used to establish routes for streams
- Stream frames are used to convey data streams (begin, data, end; window and reset)
- Streams are unidirectional

[![Build Status][build-status-image]][build-status]

[build-status-image]: https://travis-ci.org/reaktivity/nukleus.spec.svg?branch=develop
[build-status]: https://travis-ci.org/reaktivity/nukleus.spec
