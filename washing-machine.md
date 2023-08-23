![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
Topic: v1cdti/hw/get/6310301034/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "150"
}

## Get firmware version
Topic: v1cdti/hw/get/6310301034/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "get firmware",
    "value"     : "20"
}

## Get manufacture id and geo-location or location placement
Topic: v1cdti/hw/get/6310301034/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "manufacture id",
    "value"     : "A",
    "location"  : "Bangkok"
}


## Set geo-location or location placement
Topic: v1cdti/hw/set/6310301034/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Bangkok"
}

## Monitor machine sensor
Topic: v1cdti/hw/monitor/6310301034/model-01/WSH-SN001
Payload: {
"action"    : "monitor",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "Round",
    "value"     : "1000"
}

## Set machie status to "maint" to indicate this machine need to be maintenance.
Topic: v1cdti/hw/set/6310301034/model-01/WSH-SN001
Payload: {
"action"    : "set",
    "project"   : "6310301034",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "maint"
}