<h1 align="center">🦋 Network Intrusion Detection using Autoencoders 🦋</h1>

A simple autoencoder which can classify a request of a network is a normal one or not.

## Description
-Developed an anomaly detection system for network traffic using autoencoders. The project focused on identifying unusual patterns in network data that could indicate potential security threats, such as intrusions, malware activities, or other cyber-attacks. 
-Autoencoders are a type of neural Network used for unsupervised learning. Here we are classifying requests as malicious or not.
-The Dataset consists of 42 features . They are respectively
    'duration', 'protocol_type', 'service', 'flag', 'src_bytes',
   'dst_bytes', 'land', 'wrong_fragment', 'urgent', 'hot',
   'num_failed_logins', 'logged_in', 'num_compromised', 'root_shell',
   'su_attempted', 'num_root', 'num_file_creations', 'num_shells',
   'num_access_files', 'num_outbound_cmds', 'is_host_login',
   'is_guest_login', 'count', 'srv_count', 'serror_rate',
   'srv_serror_rate', 'rerror_rate', 'srv_rerror_rate', 'same_srv_rate',
   'diff_srv_rate', 'srv_diff_host_rate', 'dst_host_count',
   'dst_host_srv_count', 'dst_host_same_srv_rate',
   'dst_host_diff_srv_rate', 'dst_host_same_src_port_rate',
   'dst_host_srv_diff_host_rate', 'dst_host_serror_rate',
   'dst_host_srv_serror_rate', 'dst_host_rerror_rate',
   'dst_host_srv_rerror_rate', 'class'
   
## Libraries Needed
- NumPy
- Pandas
- Matplotlib
- Tensorflow

## Accuracy
- F1 Score: 0.8787
- Precision: 0.7983
- Recall: 0.9772
- Confusion Matrix: [[2090  584]
                     [  54 2311]]

## Conclusion
This Autoencoder model will help us to identify a request is malicious or not.
