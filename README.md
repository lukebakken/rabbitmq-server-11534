## Setup

* Add `rmq0.local`, `rmq1.local`, and `rmq2.local` in your `hosts` file with IP address `127.0.0.1`

*
    ```
    git submodule update --init
    make -C rabbitmq-server
    ```

## Bring up a cluster

* Open three terminals in this directory
* In one terminal, run `make start-rmq0`
* In another terminal, run `make start-rmq1`
* In the last terminal, run `make start-rmq2`
