Создадим коммит с описанием prepare for merge and rebase и отправим его в ветку main.
	git commit -m 'prepare for merge and rebase'
Создайте ветку git-merge. 
	git checkout -b git-merge
Замените в ней содержимое файла merge.sh 
Создайте коммит merge: @ instead * отправьте изменения в репозиторий
	git add merge.sh
	git commit -m 'merge: @ instead *'
	git push origin
И разработчик подумал и решил внести еще одно изменение в merge.sh
Создайте коммит merge: use shift и отправьте изменения в репозиторий.
	git add merge.sh
	git commit -m 'merge: use shift'
	git push origin
	