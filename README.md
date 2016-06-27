# sessionSeven-Assignment1-

1.	Store data in sequence file format

    result.saveAsSequenceFile(path) 
    
2.	To read from a sequence file,  we need to import some packages:

    Import  org.apache.hadoop.io.Text
    
    Import org.apache.hadoop.io.IntWritable
    
    val result = sc.sequenceFile(path)

