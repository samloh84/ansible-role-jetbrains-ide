Testing:
```ansible-playbook jetbrains-ide/tests/main.yml```


```ansible-playbook -e "product=idea product_version=2016.2.4" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=clion product_version=2016.2.2" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=datagrip product_version=2016.2.3" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=pycharm product_version=2016.2.3" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=rubymine product_version=2016.2.3" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=phpstorm product_version=2016.2.1" jetbrains-ide/tests/main.yml```
```ansible-playbook -e "product=webstorm product_version=2016.2.1" jetbrains-ide/tests/main.yml```
