# Set up an Internal web server on Windows

## Introduction:

Today, we're diving into the installation and setup of Windows IIS Webserver on our Domain Controller (DC). This guide aims to simplify the process, ensuring a seamless integration of IIS for hosting websites within our network environment.

## Getting Started:

Let's begin by exploring the steps involved in installing and configuring Windows IIS Webserver on our Domain Controller.

## Installation Steps:

1. **Access Server Manager**: Open Server Manager on your Domain Controller.

2. **Add Roles and Features**: Navigate to "Manage" and select "Add Roles and Features."

3. **Role-Based or Feature-Based Installation**: Choose "Role-based or feature-based installation."

4. **Select Server**: Ensure your Domain Controller is selected as the destination server.

5. **Select Role**: From the list of available roles, choose "Web Server (IIS)."

6. **Add Features**: Click "Add Features" to include additional required features.

7. **Confirmation**: Review the selected features and click "Install" to begin the installation process.

## Configuration Steps:

1. **Access IIS Manager**: Once installation is complete, access the Internet Information Services (IIS) Manager.

2. **Website Creation**: Create a new website by right-clicking on "Sites" and selecting "Add Website."

3. **Site Information**: Provide necessary information such as site name, physical path, and binding information.

4. **Configure Binding**: Configure bindings to specify IP address, port, and hostname for the website.

5. **Access Permissions**: Set permissions for website access as per your requirements.

6. **Testing**: Test the website by accessing it through a web browser to ensure proper functionality.

# Conclusion:

With these simplified steps, you'll be able to install and set up Windows IIS Webserver on your Domain Controller with ease. This enhancement to your network environment opens up opportunities for hosting websites internally, facilitating smoother operations within your organization.
