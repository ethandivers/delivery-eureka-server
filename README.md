# 🚀 delivery-eureka-server - Seamless Service Discovery for Delivery Systems

[![Download delivery-eureka-server](https://img.shields.io/badge/Download%20Now-Get%20Started-4CAF50?logo=github)](https://github.com/ethandivers/delivery-eureka-server/releases)

## 📋 Description

delivery-eureka-server is the Service Discovery Server for the Guavapay Delivery microservice ecosystem. It uses Spring Cloud Netflix Eureka to allow all other services, such as gw-delivery, ms-delivery-admin, ms-courier-order, and ms-parcel-order, to register and discover each other dynamically without hardcoding hostnames or ports. This makes your service operations smoother and more efficient.

## 🚀 Getting Started

Follow these simple steps to download and run delivery-eureka-server on your system. You will need a compatible environment, detailed below.

### 🔍 System Requirements

- **Operating System:** Windows 10 or above, MacOS, or Linux
- **Java Version:** JDK 11 or higher installed. You can download it [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
- **Memory:** At least 512 MB of RAM
- **Disk Space:** A minimum of 100 MB free disk space

### 📥 Download & Install

1. **Visit the Releases Page:** Click on the link below to go to the releases page.
   
   [Download delivery-eureka-server](https://github.com/ethandivers/delivery-eureka-server/releases)

2. **Select the Latest Release:** Look for the latest version. It usually displays at the top of the page.

3. **Download the File:** Click on the `.jar` file. This will start the download.

4. **Move the File:** Once downloaded, move the file to a directory you can access easily.

### ⚙️ Running the Application

1. **Open a Terminal or Command Prompt:**
   - **Windows:** Press `Win + R`, type `cmd`, and hit `Enter`.
   - **MacOS:** Open `Terminal` from the Applications folder or use Spotlight (`Cmd + Space`).
   - **Linux:** Open your terminal application.

2. **Navigate to the Directory:**
   Use the `cd` command to change to the directory where you saved the `.jar` file. For example:
   ```bash
   cd path/to/your/directory
   ```

3. **Run the Application:**
   Use this command to start the delivery-eureka-server:
   ```bash
   java -jar delivery-eureka-server.jar
   ```

4. **Access the Server:** Open your web browser and go to `http://localhost:8761/` to access the Eureka dashboard.

### 🛠️ Configuration Options

You can modify how delivery-eureka-server runs by using configuration files. Here are a few basic settings:

- **Server Port:** Change the port by editing the `application.properties` file. Add or modify the line:
  ```
  server.port=8761
  ```
- **Service Name:** You can set your service's name:
  ```
  spring.application.name=delivery-eureka-server
  ```

### ✅ Basic Usage

Once the server is running, you can:

- Register additional services by pointing them to the `delivery-eureka-server`.
- Monitor available services on the Eureka dashboard.

### 📊 Features

- **Dynamic Service Registration:** Services can register themselves and find others without hardcoding addresses.
- **Health Checks:** The server can monitor the health of registered services.
- **Dashboard:** A user-friendly web interface to view registered services.

## 🔗 Additional Resources

- GitHub Repository: [delivery-eureka-server](https://github.com/ethandivers/delivery-eureka-server)
- Documentation for Spring Cloud Netflix Eureka: [Spring Cloud](https://spring.io/projects/spring-cloud)

## 📞 Support

If you encounter any issues or have questions, feel free to raise an issue on the GitHub repository or contact the maintainers for assistance.

---

With these steps, you can successfully download and run the delivery-eureka-server. Enjoy the power of seamless service discovery for your applications!