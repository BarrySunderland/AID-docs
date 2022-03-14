## Error Code

The terminal program may exit in several cases with an error code. In most cases, they follow the pattern below

* ```0```: Success.
* ```1```: Internal unknown error.
* ```2```: Communication error with third-party servers. The requested URL should have been explicitly stated in the log file (or terminal).
* ```3```: Database error, like conflicts in relations, etc.
* ```4```: Request cannot be understood.
* ```5```: Docker error.
* ```6```: Internal Error caused by packages.