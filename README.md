# eCQM Implementation Guide

This project outlines a methodology for developing and executing Electronic Clinical Quality Measures.

## Local Build

The HL7 IG Publisher is committed to this repository to make building as easy as possible. To build locally, clone the repository and issue the following command in the root:

    java -jar "org.hl7.fhir.igpublisher.jar" -ig ig.json

## Dependencies

Before the instructions in the above "Local Build" section will work, you
need to install several primary dependencies.

### Java

Go to [http://www.oracle.com/technetwork/java/javase/downloads/](
http://www.oracle.com/technetwork/java/javase/downloads/) and download the
latest (version 8 or higher) JDK for your platform, and install it.

### Ruby

Jekyll requires Ruby version 2.1 or greater.  Depending on your operating
system, you may already have Ruby bundled with it.  Otherwise, or if you
need a newer version, go to [https://www.ruby-lang.org/en/downloads/](
https://www.ruby-lang.org/en/downloads/) for directions.

### Jekyll

Go to [https://jekyllrb.com](https://jekyllrb.com) and follow the
instructions there, for example `gem install jekyll bundler`.  The end
result of this should be that thebinary "jekyll" is now in your path.