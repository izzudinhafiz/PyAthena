.. _api_filesystem:

File System Integration
=======================

This section covers S3 filesystem integration and object management.

S3 FileSystem
-------------

.. autoclass:: pyathena.filesystem.s3.S3FileSystem
   :members:

S3 Objects
----------

.. autoclass:: pyathena.filesystem.s3_object.S3Object
   :members:

.. autoclass:: pyathena.filesystem.s3_object.S3ObjectType
   :members:

.. autoclass:: pyathena.filesystem.s3_object.S3StorageClass
   :members:

S3 Upload Operations
--------------------

.. autoclass:: pyathena.filesystem.s3_object.S3PutObject
   :members:

.. autoclass:: pyathena.filesystem.s3_object.S3MultipartUpload
   :members:

.. autoclass:: pyathena.filesystem.s3_object.S3MultipartUploadPart
   :members:

.. autoclass:: pyathena.filesystem.s3_object.S3CompleteMultipartUpload
   :members: