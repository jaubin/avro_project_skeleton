# avro_project_skeleton
It is generally a good practice to store Avro schemas in a single location to avoid project inter-dependencies. The goal of this project is to provide a skeleton so that the Avro schemas you create could be used easily to generate various corresponding classes in different languages.

File src/main/avro/example.avsc is there only for documentation purpose and can be safely removed. However it is located where your Avro schema files should be stored.

# Acknowledgement

For C#, this project uses avrogen library from project https://github.com/confluentinc/avro/releases - this library is released under the Apache 2.0 license.
