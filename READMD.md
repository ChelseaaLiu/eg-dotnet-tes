# A Dotnet Example <!-- omit in toc -->

## 1. Target Framework

.NET 8

## 2. How to Use a .NET Project Downloaded from GitHub

To set up and run a .NET project downloaded from GitHub, follow these steps:

### 2.1. Ensure Your Environment

Make sure you have the following tools installed in your development environment:

- .NET SDK (download and install from the [Microsoft official website](https://dotnet.microsoft.com/download))
- IDE (such as Visual Studio or Visual Studio Code)

### 2.2. Download the Project

You can download the project from GitHub in the following ways:

- **Using Git to Clone the Project:**
  Open a terminal or command prompt and run the following command:

  ```bash
  git clone <repository-url>
  ```

  Replace `<repository-url>` with the URL of the GitHub repository. For example:

  ```bash
  git clone https://github.com/ChelseaaLiu/eg-dotnet-test.git
  ```

- **Download the ZIP File:**
  Directly download the ZIP file from the GitHub project page and extract it to a local directory.

### 2.3. Open the Project

Open your IDE and open the folder containing the project you just downloaded.

### 2.4. Restore Dependencies

In the project root directory, run the following command to restore the project's dependencies:

```bash
dotnet restore
```

### 2.5. Build and Run the Project

Run the following commands to build and run the project:

```bash
dotnet build
dotnet run
```

This will compile the project and start it.

### 2.6. Configuration and Other Settings (if needed)

Depending on the project's requirements, you might need to do some configuration, such as setting up database connection strings, API keys, etc. These are usually set in `appsettings.json` or other configuration files.

### 2.7. Example

Assume you downloaded a project named `MyDotNetApp` from GitHub, here are the complete steps:

1. Clone the project:

   ```bash
   git clone https://github.com/ChelseaaLiu/eg-dotnet-test.git
   cd MyDotNetApp
   ```

2. Restore dependencies:

   ```bash
   dotnet restore
   ```

3. Build and run the project:

   ```bash
   dotnet build
   dotnet run
   ```

## 3. New dotnet application

```bash
dotnet new console --framework net8.0 --use-program-main
```

## 4. Debug

- Please press Ctrl+Shift+P and enter `.NET: Generate Assets for Build and Debug`

##
