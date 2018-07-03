# DiskMonitorDataType {#DiskMonitorDataType .reference}

Type of disk monitoring data.

## Node Name {#section_pf3_fjp_ydb .section}

DiskMonitorData

## Subnode {#ResponseParameter .section}

|Name|Type|Description|
|:---|:---|:----------|
|DiskId|String|ID of the disk.|
|Bpsread|Integer|Disk read bandwidth, measured in Byte/s.|
|Bpswrite|Integer|Disk write bandwidth, measured in Byte/s.|
|BPSTotal|Integer|Total disk read and write bandwidth, measured in Byte/s.|
|IOPSRead|Integer|Disk IO reads, measured in /s.|
|IOPSWrite|Integer |Disk IO writes, measured in /s.|
|IOPSTotal|Integer|Total disk IO read and write operations, measured in /s.|
|Latencyread|Integer|Read latency of a disk, measured in Byte/s.|
|Write latency of a disk, measured in Byte/s.|Integer|Write latency of a disk, measured in Byte/s.|
|TimeStamp|String|Time stamp of the query, which is presented according to [ISO8601](intl.en-US/API Reference/Appendix/ISO 8601 time format.md#), and UTC time is used. The format is  YYYY-MM-DDThh:mmZ.|

