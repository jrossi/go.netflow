# go.netflow

This is a work-in-progress NetFlow v9 (RFC 3954) collector in Go.

## Installation

```
go get github.com/brooksbp/go.netflow
```

## Usage

```
cd $GOPATH/src/github.com/brooksbp/go.netflow/collector
go build

./collector
Error:  Unknown template=256 {{9 4 210006370 8401677 6234 0} []}
Error:  Unknown template=256 {{9 4 210008370 8401679 6235 0} []}
Error:  Unknown template=256 {{9 8 210010370 8401681 6236 0} []}
LAST_SWITCHED: 12 132 72 144  FIRST_SWITCHED: 12 131 246 146  IN_PKTS: 0 0 0 23  IN_BYTES: 0 0 11 144  INPUT_SNMP: 0 0 0 2  OUTPUT_SNMP: 0 0 0 13  IPV4_SRC_ADDR: 2.110.97.21 IPV4_DST_ADDR: 192.168.88.20 PROTOCOL: 17  SRC_TOS: 0  L4_SRC_PORT: 63 96  L4_DST_PORT: 199 147  IPV4_NEXT_HOP: 192.168.88.20 DST_MASK: 0  SRC_MASK: 0  TCP_FLAGS: 0  IN_DST_MAC: d4:ca:6d:84:30:89 OUT_SRC_MAC: d4:ca:6d:84:30:8a
LAST_SWITCHED: 12 132 82 14  FIRST_SWITCHED: 12 132 82 14  IN_PKTS: 0 0 0 5  IN_BYTES: 0 0 3 69  INPUT_SNMP: 0 0 0 2  OUTPUT_SNMP: 0 0 0 13  IPV4_SRC_ADDR: 104.50.234.172 IPV4_DST_ADDR: 192.168.88.20 PROTOCOL: 17  SRC_TOS: 0  L4_SRC_PORT: 234 14  L4_DST_PORT: 199 147  IPV4_NEXT_HOP: 192.168.88.20 DST_MASK: 0  SRC_MASK: 0  TCP_FLAGS: 0  IN_DST_MAC: d4:ca:6d:84:30:89 OUT_SRC_MAC: d4:ca:6d:84:30:8a
..
```
