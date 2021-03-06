# 4.2 Black-box Test Techniques

Equivalence partitioning divides data into partitions \(also known as equivalence classes\) in such a way that all the members of a given partition are expected to be processed in the same way \(see Kaner 2013 and Jorgensen 2014\). There are equivalence partitions for both valid and invalid values.

* Valid values are values that should be accepted by the component or system. An equivalence partition containing valid values is called a “valid equivalence partition.” 
* Invalid values are values that should be rejected by the component or system. An equivalence partition containing invalid values is called an “invalid equivalence partition.” 
* Partitions can be identified for any data element related to the test object, including inputs, outputs, internal values, time-related values \(e.g., before or after an event\) and for interface parameters \(e.g., integrated components being tested during integration testing\). 
* Any partition may be divided into sub partitions if required. 
* Each value must belong to one and only one equivalence partition. 
* When invalid equivalence partitions are used in test cases, they should be tested individually, i.e., not combined with other invalid equivalence partitions, to ensure that failures are not masked. Failures can be masked when several failures occur at the same time but only one is visible, causing the other failures to be undetected.

To achieve 100% coverage with this technique, test cases must cover all identified partitions \(including invalid partitions\) by using a minimum of one value from each partition. Coverage is measured as the number of equivalence partitions tested by at least one value, divided by the total number of identified equivalence partitions, normally expressed as a percentage. Equivalence partitioning is applicable at all test levels.

