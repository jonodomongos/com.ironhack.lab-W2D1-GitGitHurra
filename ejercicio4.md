  01  git checkout -b rama1\n
  02  git add .\ngit commit -m "Cambios en rama1"\n
  03  git checkout main\n
  04  git add .\ngit commit -m "Cambios en main"\n
  05  git merge rama1\n
  06  git add index.html\ngit commit -m "Conflicto resuelto"\n
  07  git commit -m "first commit"\ngit branch -M main\ngit remote add origin https://github.com/jonodomongos/com.ironhack.lab-W2D1-GitGitHurra.git\ngit push -u origin main
  08  git add .\ngit commit -m "Actualización index"\n
  09  git push\n
  10  git clone https://github.com/usuario/lab4-gitbash.git\ncd lab4-gitbash\n
  11  git clone https://github.com/jonodomongos/lab4-gitbash.git\ncd lab4-gitbash\n
  12  nano notas.txt\n
  13  git add .\ngit commit -m "Primer commit desde bash"\n
  14  echo "Otra línea" >> notas.txt\n
  15  git add .\ngit commit -m "Segundo commit"\n
  16  git push\n