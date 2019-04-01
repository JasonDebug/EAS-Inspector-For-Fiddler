# EAS Inspector for Fiddler

This application decodes EAS requests and responses into readable XML in a Fiddler Inspector. It will can provide a more complete rendering of EAS traffic than what Exchange provides with its own tracing.

It should work with all versions of Exchange back to Exchange 2003. You can use this to troubleshoot EAS issues off of a saved Fiddler log or in real-time.

*Fork Info:*
This fork of [dseph's](https://github.com/dseph/EAS-Inspector-For-Fiddler) repo decouples the ASWBXML component from the Fiddler extension into its own project. The library can then be used in other projects (Fiddler or not).