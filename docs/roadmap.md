## Ideas
* Improve basic array type support
  * https://github.com/eclipse-sparkplug/sparkplug/issues/61
* Make more use of Protobuf scalar types:
  * https://github.com/eclipse-sparkplug/sparkplug/issues/62
* Birth retain/split metadata - prevent new Host Applications from being so disruptive
  * https://github.com/eclipse-sparkplug/sparkplug/issues/96
  * https://github.com/eclipse-sparkplug/sparkplug/issues/209
* Allow historical data to be published on QoS1
  * https://github.com/eclipse-sparkplug/sparkplug/issues/97
* Add engineering units as a first level metric property
  * https://github.com/eclipse-sparkplug/sparkplug/issues/104
* Cleanup syntax of examples in the spec (i.e. how to represent payloads in a human readible form):
  * https://github.com/eclipse-sparkplug/sparkplug/issues/114
  * https://github.com/eclipse-sparkplug/sparkplug/issues/185
* Allow for re-use of the payload timestamps to be used for metrics in that payload
  * https://github.com/eclipse-sparkplug/sparkplug/issues/124
* Add support for DBIRTHs to include Template definitions
  * https://github.com/eclipse-sparkplug/sparkplug/issues/130
* Add concept of 'quality context' to the spec
  * https://github.com/eclipse-sparkplug/sparkplug/issues/145
* Remove PropertySetList
  * https://github.com/eclipse-sparkplug/sparkplug/issues/204
* Add protobuf extensions on metrics
  * https://github.com/eclipse-sparkplug/sparkplug/issues/224
* JSON encoding standard for payloads
  * https://github.com/eclipse-sparkplug/sparkplug/issues/231
* Increase timestamp resolution to more than milliseconds
  * https://github.com/eclipse-sparkplug/sparkplug/issues/232
* Create a Group ID or ID delimiter: i.e. spBv1.0/plantA:line1:cell5/NDATA/nodeID
  * https://github.com/eclipse-sparkplug/sparkplug/issues/261
* Allow metrics to be included in the topic
  * https://github.com/eclipse-sparkplug/sparkplug/issues/262
* Add identifier to CMD payloads to denote source of the command
  * https://github.com/eclipse-sparkplug/sparkplug/issues/306
* Partial DataSet Publishing in DATA messages
  * https://github.com/eclipse-sparkplug/sparkplug/issues/324
* Add support for Records (e.g. NRECORD and DRECORD verbs)
* Add compression support for payloads
* Multiple Host ID support for Edge Nodes - or secondary hosts?
* Expand Sparkplug Aware MQTT Server definition to include automatic BIRTH delivery
* Expand Sparkplug Aware MQTT Server definition to include automatic expansion of DATA and BIRTH metric content into individual topics
* Expand Sparkplug Aware MQTT Server definition to a REST API for querying metadata
* Expand Sparkplug Aware MQTT Server definition to a REST API for querying most recent data and for connectionless publishing of DATA and BIRTH messages
* Add strong data typing for inputs and output to commands as part of BIRTH or METADATA
* Implement a reliable request/response mechanism so that commands can return data, error codes, or other result content
* Consider eliminating group/node/edge IDs altogether and allowing a flexible hiearchy using namespace/message_type/any_hiearchy (note that this would not break existing apps given a new namespace for the next version of SpB)
* Add new primitive types for location and generic JSON
* Separate data and metadata in BIRTH messages and leverage the MQTT retain flag to optimize/minimize load on edge nodes and to enable application tooling to discover metadata even if an edge node is offline
* Clarify which components of a Sparkplug metric are mandatory and which are optional



## To Investigate
* https://github.com/eclipse-sparkplug/sparkplug/issues/174
* https://github.com/eclipse-sparkplug/sparkplug/issues/195
* https://github.com/eclipse-sparkplug/sparkplug/issues/196
