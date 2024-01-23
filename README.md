# Base Image Development Environments

This repository contains the Vagrant configurations for a range of base images catering to various development needs, including DevOps, Flutter mobile app development, and Unreal Engine 5 game development.

## Supported Operating Systems

- **FreeBSD 13** (Needs Update)
- **Kali Linux** (TODO: Specific tasks to be completed)
- **Amazon Linux 2**
- **Rocky Linux 9**
- **Ubuntu 22.04**

Each operating system has its own directory with the respective Vagrant configuration files and provisioning scripts.

## Getting Started

To use these environments, you need to have Vagrant and VirtualBox (or your preferred provider) installed on your machine. Follow the steps below to get started:

1. **Install Vagrant:**
   - Visit [Vagrant Downloads](https://www.vagrantup.com/downloads) and download the appropriate package for your operating system.

2. **Install VirtualBox OR Vmware:**
   - Download VirtualBox from [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads).
   - Download VMware Workstation from [VMware Workstation Downloads](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html).

3. **Clone this Repository:**
```
git clone https://your-repository-url-here
cd into-the-cloned-directory
```

4. **Start a Development Environment:**
```
cd into-the-specific-os-directory
vagrant up
```

5. **Access the Development Environment:**
```
vagrant ssh
```


## Customization

You can customize each base image according to your project requirements. The Vagrant files are configured to provision the environments using Ansible, which allows for easy customization and configuration.

## Contributing

If you have suggestions for improving these base images or want to contribute configurations for additional operating systems, please feel free to create a pull request or open an issue.

## License

This project is licensed under the BSD 2-Clause License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Base configurations provided by [Your Name or Organization].
- Special thanks to all contributors and maintainers of the software used in these base images.

