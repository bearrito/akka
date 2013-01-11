Multi-Node Test Sample
======================

This sample is meant to be used by studying the code; it does not perform any
astounding functions when running it. If you want to run it, check out the akka
sources on your local hard drive, follow the [instructions for setting up Akka
with SBT](http://doc.akka.io/docs/akka/current/intro/getting-started.html).
When you start SBT within the checked-out akka source directory, you can run
this sample by typing

    akka-sample-multi-node-experimental/multi-jvm:test-only sample.multinode.MultiNodeSampleSpec

(You might have to pass a system property containing `akka.test.tags.include=long-running`.)

You can read more in the [Akka docs](http://akka.io/docs).