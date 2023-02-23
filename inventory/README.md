group_vars/test 使用 `ansible-vault encrypt group_vars/test` 命令加密，该文件中包含了 test 主机组所需的密码变量

直接使用 `ansible -i inventory/test.yaml all -m ping -e @inventory/test_password.yaml` 命令以使用本地的密码文件
