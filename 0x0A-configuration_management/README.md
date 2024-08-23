# 0x0A. Configuration management



## Technologies Used

- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Emacs](https://img.shields.io/badge/Emacs-7F5AB6.svg?style=for-the-badge&logo=gnu-emacs&logoColor=white)
- ![Vim](https://img.shields.io/badge/Vim-019733.svg?style=for-the-badge&logo=vim&logoColor=white)
- ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
- ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
- ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
- ![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)



## Resource

- [Intro to Configuration Management](https://www.digitalocean.com/community/tutorials/an-introduction-to-configuration-management)
- [Puppet resource type: file](https://puppet.com/docs/puppet/5.5/types/file.html) (*Check "Resource types" for all manifest types in the left menu*)
- [Puppet’s Declarative Language: Modeling Instead of Scripting](https://puppet.com/blog/puppets-declarative-language-modeling-instead-of-scripting/)
- [Puppet lint](http://puppet-lint.com/)
- [Puppet emacs mode](https://github.com/voxpupuli/puppet-mode)
- [Puppet CookBook](https://www.puppetcookbook.com/)

## Installing `puppet` and `puppet-lint`

```sh
# installing puppet and puppet-lint
wget https://apt.puppet.com/puppet7-release-focal.deb && \
    dpkg -i puppet7-release-focal.deb && \
    apt-get update && \
    apt-get install puppet-agent puppet-lint -y

# confirming installation
puppet -V
puppet-lint -v

# If you get an error saying puppet command not found, source the path
source /etc/profile.d/puppet-agent.sh
```

## Tasks

<details>
<summary><a href="./0-create_a_file.pp">0. Create a file</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/NM2k46hX/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./1-install_a_package.pp">1. Install a package</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/PqVvKj7c/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./2-execute_a_command.pp">2. Execute a command</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/CxZFC13P/image.png' border='0' alt='image'/></a>
</details>
