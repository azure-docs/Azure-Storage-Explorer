# Download Azure Storage Explorer

Azure Storage Explorer is a versatile standalone application that simplifies the management of your Azure Storage data. Whether you are working with Blob Storage, File Storage, Queues, Tables, or Managed Disks, this tool provides an intuitive and efficient way for developers and administrators to interact with their storage resources seamlessly.

- [Installation](#installation)
- [System Requirements](#system-requirements)
- [Connecting to Storage](#connecting-to-storage)
   - [Signing in with Azure Active Directory](#signing-in-with-azure-active-directory)
   - [Using Storage Account Name](#using-storage-account-name)
   - [Connecting via Shared Access Signatures (SAS)](#connecting-via-shared-access-signatures-sas)
- [Resources](#resources)

## Installation

Download Azure Storage Explorer for Windows and get started instantly by clicking the button below:

[**Download Azure Storage Explorer**](*)

Azure Storage Explorer streamlines cloud storage management with an intuitive interface and direct access to your Azure resources. Get the latest version, install it on your system, and connect using your Azure credentials or access keys. Whether you're handling Blobs, Queues, or Tables, this tool delivers the flexibility and efficiency required for an optimized workflow.

## System Requirements

### Windows
- **OS:** Windows 10 or later (64-bit only)
- **Processor:** 1.4 GHz or higher
- **RAM:** At least 4 GB
- **Disk Space:** Minimum 500 MB of free space

### macOS
- **OS:** macOS 10.12 (Sierra) or later
- **Processor:** Intel-based
- **RAM:** At least 4 GB
- **Disk Space:** Minimum 500 MB of free space

### Linux
- **Supported Distributions:** Ubuntu 18.04+, Fedora 30+, CentOS 8+
- **Processor:** 1.4 GHz or higher
- **RAM:** At least 4 GB
- **Disk Space:** Minimum 500 MB of free space

---

## Connecting to Storage

Azure Storage Explorer offers multiple authentication methods to establish connections with storage accounts efficiently.

### Signing in with Azure Active Directory
1. Open Azure Storage Explorer.
2. Click "Add an Account" in the navigation panel.
3. Authenticate with your Azure Active Directory credentials.
4. Once logged in, your associated subscriptions will be automatically displayed.

### Connecting via Storage Account Name
1. Obtain your storage account name and access key from the Azure portal.
2. In Storage Explorer, choose "Connect to Azure Storage" and select "Storage account name and key."
3. Enter the relevant details and specify a recognizable display name.
4. Confirm the settings to complete the connection.

### Establishing a Connection with Shared Access Signatures (SAS)
1. Generate a SAS token in the Azure portal.
2. In Storage Explorer, choose "Use a shared access signature (SAS) URI" as the authentication method.
3. Paste the SAS URI and validate the connection.
4. You will now have access to the associated storage resources.

### Local Emulator Integration
- Azure Storage Explorer supports connections to local emulators like Azurite.
- Provide the emulator’s URL when configuring connection settings.

---

## Managing Your Storage Data

Azure Storage Explorer includes a comprehensive set of tools to help manage various types of storage resources efficiently.

### Blob Storage
- **Core Capabilities:** Upload, download, copy, delete, and modify blob data.
- **Common Use Cases:** Storing unstructured data, hosting images, backups.

### File Storage
- **Core Capabilities:** Navigate file structures, upload, download, and organize files.
- **Common Use Cases:** Cloud-based file sharing, seamless data migration.

### Queues
- **Core Capabilities:** Create, modify, and manage message queues.
- **Common Use Cases:** Task scheduling, asynchronous messaging systems.

### Tables
- **Core Capabilities:** Query, modify, and delete table data.
- **Common Use Cases:** Storing semi-structured data, managing key-value datasets.

### Managed Disks
- **Core Capabilities:** View, duplicate, and manage disk snapshots.
- **Common Use Cases:** Data recovery, disaster backup solutions.

---

## Advanced Capabilities

- **Access Management:** Implement role-based access control (RBAC) and set up shared access policies.
- **Storage Insights:** Monitor logs and track key performance metrics.
- **Seamless Integrations:** Works smoothly with Azure Functions, Logic Apps, and other services.
- **Customization Settings:** Adjust network preferences and proxy configurations for optimized usage.
