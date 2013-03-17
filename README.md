AutoFlowControl
==================

AutoFlowControl is a cyclic-cascaded MapReduce scheduling tool. It has three
features:

* It uses batch processing instead of stream processing.
* It makes the best use of resource, so it has high utilization.
* It keeps the source of input more up-to-date, i.e., the feedback is rapidly
  reflected to the input data source.

The background used here is MapRedcue, however, it can be extended to more
general task processors and processing patterns.

