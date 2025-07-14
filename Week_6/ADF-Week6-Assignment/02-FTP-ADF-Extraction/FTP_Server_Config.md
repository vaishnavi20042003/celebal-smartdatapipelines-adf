# FTP Server Integration in ADF

Steps:
1. Configure an FTP linked service in ADF
2. Use connection string:
   - Host: `ftp.example.com`
   - Port: `21`
   - Auth: Username + Password
3. Create an FTP dataset pointing to `ftp_sample_file.csv`
4. Build a pipeline using "Copy Activity" to ingest FTP data