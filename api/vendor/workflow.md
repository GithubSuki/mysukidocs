# Work Flow

_Updated May 10, 2020 Victor Javier_
_WORK IN PROGRESS_

### Current Status

| action           | status     | Message                                                                         |
| ---------------- | ---------- | ------------------------------------------------------------------------------- |
|                  | new        | Tell user that to wait for acceptance                                           |
| `accepted`       | accepted   | Tell the user what have accepted, submitting for picking                        |
| `pick/start`     | preparing  | Tell the user that we have started picking                                      |
| `pick/end`       | delivering | Tell the user that we are done preparing, waiting for QA to double check        |
| `check/start`    | delivering | Checking started                                                                |
| `check/end`      | delivering | Checking done, you may now make the payment, if paid, ready for pickup/delivery |
| `print/waiting`  | delivering |
| `print/start`    | delivering |
| `print/end`      | delivering |
| `delivery/start` | delivering | Its now on its way to you                                                       |
| `delivery/end`   | received   | Thank you                                                                       |
