Git revert dùng để lùi lại commit trước đó

git sẽ đè lên một commit revert không ảnh hưởng gì tới commit trước đó

# Revert một commit 
source code sẽ là source code mới và chỉ bỏ đi code phần commit bị revert
```shell
git revert <mã hash của commit>
```
# Revert nhiều commit:
source code sẽ là phần code hiện tải bỏ đi các commit bị revert
```shell
git revert HEAD~<số lượng commit muốn revert>
```

# Quay lại commit đã từng bị revert
```shell
git revert <mã hash của commit dùng để revert commit bị revert>
```