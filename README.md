# devops-netology
devsys-2

first edit
secoond edit
third edit

a. Файл .gitignore в корневой директории пуст, поэтому никаких исключение не будет.


b. Файл /Terraform/.gitignore  содержит шаблоны для исключений:

1. строки, начинающиеся с '#' - игнорируются (комментарии)


2. **/.terraform/* -Рекурсивно все директории ./terraform/ игнорируются (* - любой набор символов(цифр))

3. Файлы по шаблонам *.tfstate и *.tfstste.* - игнорируются рекурсивно 

4. Файлы названием  crash.log игнорируются рекурсивно

5  Файлы по шаблону *.tfvars игнорируются рекурсивно

6. Файлы override.tf, override.tf.json - игнорируются рекурсивно, файлы по шаблонам *_override.tf и *_override.tf.json игнорируются рекурсивно

7. Файлы .terraformrc и terraformrc игнорируются рекурсивно

make new branch 'fix'