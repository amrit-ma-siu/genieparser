    --------------------------------------------------------------------------------
                                New
    --------------------------------------------------------------------------------
    * NXOS
        * Modified ShowRunInterface:
            * Added parsing support (schema and parsers) for the following outputs
                * no switchport (switchport is default)
                * mtu 1500
                * ip address 10.1.1.1/30
                * vrf member test-vrf
            * show running-config interface
            * show running-config | section ^interface
            * Moved all regex match to before the loop
        * created respective test folder and files under nxos/tests/ShowRunningConfigInterface/