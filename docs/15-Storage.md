Storage
The storage engine is the primary component of MongoDB responsible for managing data. MongoDB provides a variety of storage engines, allowing you to choose one most suited to your application.

The journal is a log that helps the database recover in the event of a hard shutdown. There are several configurable options that allows the journal to strike a balance between performance and reliability that works for your particular use case.

GridFS is a versatile storage system that is suited to handling large files, such as those exceeding the 16 MB document size limit.