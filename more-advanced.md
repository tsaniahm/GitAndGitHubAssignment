1. What is the difference between git reset and git revert. When would you use one over the other?

  **git reset dapat untuk melakukan penghapus catatan history dari perubahan sehingga kita tidak dapat lagi kembali ke masa depan,** 
  
  **sedangkan git revert akan membuat perubahan pada commit terbaru tanpa menghapus catatan sejarah perubahannya.**
  
2. What is the difference between git merge and git rebase. When would you use one over the other?

  **git merge dipakai untuk meleburkan state terakhir dari kedua branch kemudian di dalam branch sumber akan dibuatkan sebuah commit baru untuk menyatakan bahwa telah terjadi merging**

  **git rebase dipakaiuntuk menggabungkan sebuah branch ke ujung branch lain dengan memindahkan seluruh sejarah commit dari sebuah branch tersebut**
  
3. What is the difference between git stash pop and git stash apply. When would you use one over the other?

  **Stash akan dihapus atau menghilang ketika digunakan git stash pop sedangkan ketika digunakan git stash apply, stash yang baru saja direstore ke sumber tidak akan dihapus**
  
4. What kinds of things can you do in interactive mode when rebasing?

  **editing, deleting, and squashing**

