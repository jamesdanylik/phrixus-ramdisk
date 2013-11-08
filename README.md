Phrixus Ramdisk
=============

Implementation Notes
--------------------
Our implmentation uses an array structure to hold information about readlocks
and prevent deadlock between processes.  We succesfully copy data and close
devices, and implment another dynamic structure for holding signal data.  This
implemenation seems to work, but still hangs in some cases.

Project ToDo
------------

*	Exercise 1: osprd_process_request: perform the read or write by copying
                    data. (DONE)
*	Exercise 2: osprd_close_last: close a ramdisk and release all locks, 
                                      waking blocked processes as apporpriate.
                                      (DONE)
*	Exercise 3: osprd_ioctl: performs a ioctl on the named file.  Heavy 
                    lifiting function.(DONE?)

Project Journal
---------------
*	A change to README.
*	Made the first commit with the project skeleton.
*	Added this readme and created a repo to hold the project.

TEST CHANGES
