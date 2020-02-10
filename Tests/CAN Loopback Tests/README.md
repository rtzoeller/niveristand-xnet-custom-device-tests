# CAN Loopback Tests

These tests are designed to validate that CAN frames are being sent and received correctly in VeriStand.

## Duplicate tests?

In some cases there may be tests and system definitions which are largely identical, but with some small variation (typically additional validation/channels in one test). This is deliberate, and the tests should not be consolidated freely.

The XNET engine manipulates channel indices at runtime in order to write to the correct location. Having a single system definition with all possible additional channels enabled does not validate that this indexing is done conditionally and properly. While the goal is not to test every combination of settings, a representative set of configurations should be chosen.
