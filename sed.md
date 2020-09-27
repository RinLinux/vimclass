# sed notes




// 删除注释行和空行
sed -ri '/^[ \t]*#d;^[ \t]*$/d' file

sed -ri '/^[ \t]*|^[ \t]*$/d' file

sed -ri '/^[ \t]*($|#)/d' file 





