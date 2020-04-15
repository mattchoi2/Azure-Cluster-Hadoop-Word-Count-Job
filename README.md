# WordCount Implementation

The source for this file can be seen in the wordcountjava/src folder, and the ready-to-use .jar can be found in the wordcountjava/target folder.  After creating an Azure cluster, upload the .jar to thru an SSH connection, then run the job with the `yarn jar <jar-filepath> <input-filepath> <output-filepath>` command.

# Azure Account

![Account Proof](https://github.com/mattchoi2/Azure-Cluster-Hadoop-Word-Count-Job/blob/master/images/account.PNG?raw=true)

# Uploading Large Text File

Note this text file is larger than 90MB.   

![Text File Upload](https://github.com/mattchoi2/Azure-Cluster-Hadoop-Word-Count-Job/blob/master/images/upload.PNG?raw=true)

# Implementing WordCount

Uploading the WordCount Jar to the master node of the cluster.  

![SSH of Jar](https://github.com/mattchoi2/Azure-Cluster-Hadoop-Word-Count-Job/blob/master/images/implementation.PNG?raw=true)

# Running WordCount & Output

Running the map reduce job on the cluster.  

![Running Jar on Input](https://github.com/mattchoi2/Azure-Cluster-Hadoop-Word-Count-Job/blob/master/images/output1.PNG?raw=true)

Retrieving the output in the form of "term -> frequency" from the blob storage linked to the cluster. 

![SSH of Jar](https://github.com/mattchoi2/Azure-Cluster-Hadoop-Word-Count-Job/blob/master/images/output2.PNG?raw=true)


