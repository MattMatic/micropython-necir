# micropython-necir
NEC InfraRed receiver class for MicroPython


# Usage
    def nec_cb(nec, a, c, r)
        print(a, c, r)				# Address, Command, Repeat

    from necir import NecIr
    nec = NecIr()
    nec.callback(nec_cb)

# History
2015-04-27 Initial upload
