1. Создаем модуль go mod init PersonalArea (date: 16.06.2020);
2. Создаема файл main.go и приветственное Hello PersonalArea (date: 16.06.2020);

package main

import "fmt"

func main(){
	fmt.Println("Hello PersonalArea")
}
3. Создаем структуру проекта (Общепринятый формат https://github.com/golang-standards/project-layout):
 3.1. api;
 3.2. assets;
 3.3. build;
 3.4. cmd;
 3.5. configs;
 3.6. deplployments;
 3.7. docs;
 3.8. examples;
 3.9. githooks;
 3.10. init;
 3.11. internal;
 3.12. pkg;
 3.13. scripts;
 3.14. test;
 3.15. thrid_party;
 3.16. tools;
 3.17. vendor;
 3.18. web;
 3.19. website;
 3.20. go.mod;
 3.21. main.go;
 3.22. readme.md;

*Примечание: Данная структура стартоаая, возможно при разработке добавятся или удалятся файлы.
