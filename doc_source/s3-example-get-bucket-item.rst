.. Copyright 2010-2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

.. _aws-ruby-sdk-s3-example-get-bucket-item:

###############################################
Downloading an Object from a Bucket into a File
###############################################

The following example gets the contents of the item :code-ruby:`my-item` from the bucket
:code-ruby:`my-bucket` in the :code:`us-west-2` region, and saves it to the :file:`my-item.txt` file
in the :file:`./my-code` directory.

.. literalinclude:: ./example_code/s3/s3-ruby-example-get-item.rb
   :lines: 13-21
   :dedent: 0
   :language: ruby