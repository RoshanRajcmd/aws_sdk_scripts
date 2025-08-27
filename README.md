# aws\_sdk\_scripts

A collection of AWS SDK (Boto3) scripts for practicing and learning how to interact with AWS services using Python.

---

## Prerequisites

Before running these scripts, make sure you have the following installed and configured:

1. **Python**

   * Install Python via [pyenv](https://github.com/pyenv/pyenv) (recommended for managing Python versions per project).

2. **AWS CLI**

   * Install the AWS CLI: [AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
   * Configure your credentials:

     ```bash
     aws configure
     ```

     You will be prompted for:

     * AWS Access Key ID
     * AWS Secret Access Key
     * Default region name
     * Default output format

3. **Boto3 (AWS SDK for Python)**

   * Install boto3:

     ```bash
     pip install boto3
     ```

---

## Setup Procedure

1. **Clone this repository**

   ```bash
   git clone https://github.com/<your-username>/aws_sdk_scripts.git
   cd aws_sdk_scripts
   ```

   *Or create your own project directory if starting fresh.*

2. **Create a Python virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Create a script file**

   * Scripts don’t need a `.py` extension; you can name them directly:

     ```bash
     touch s3_list_buckets
     ```

4. **Write your script using Boto3**

   * Official docs: [Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)

5. **Make your script executable**

   ```bash
   chmod +x s3_list_buckets
   ```

6. **Run your script**

   ```bash
   ./s3_list_buckets
   ```

---

## Notes

* These scripts are for **practice and learning** only.
* Use caution when running operations that create, modify, or delete AWS resources (they may incur costs).
