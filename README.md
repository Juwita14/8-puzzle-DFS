# 8-puzzle-DFS
##Input insial state
<br/>![inputdfs](https://user-images.githubusercontent.com/56763570/78787283-f9059200-795e-11ea-8f27-6703a5d561fc.PNG)<br/>
##Input goal state
<br/>![final](https://user-images.githubusercontent.com/56763570/78787350-120e4300-795f-11ea-838c-6ee70a9704a2.PNG)<br/>
##Kemudian memanggil fungsi dfs()
variabel ans untuk menampung jumlah move dari inisial state sampai ke goal state.
<br/>![dfs](https://user-images.githubusercontent.com/56763570/78788285-6f56c400-7960-11ea-865c-6ea31a245430.PNG)<br/>
##If pertama memanggil fungsi cmp untuk memeriksa matrix saat ini apakah sudah mencapai goal state. Jika belum mencapai, maka akan memanggil fungsi getPath untuk menjadi perpindahan selanjutnya.
<br/>![cmp](https://user-images.githubusercontent.com/56763570/78788905-47b42b80-7961-11ea-93c1-a7a50caa0b51.PNG)<br/>
<br/>![path](https://user-images.githubusercontent.com/56763570/78788934-50a4fd00-7961-11ea-9b6c-f5a634585efb.PNG)<br/>
##Kemudian path tersebut akan ditambahkan sebagai child dengan cara memanggil fungsi addChilds
<br/>![child](https://user-images.githubusercontent.com/56763570/78789247-b7c2b180-7961-11ea-86a0-abbcf9185bbe.PNG)<br/>
##Memeriksa agar tidak melakukan perpindahan yang pernah dilakukan(node parent)
<br/>![visited](https://user-images.githubusercontent.com/56763570/78790426-58fe3780-7963-11ea-8277-8e3e62bb333a.PNG)<br/>
##Mengisi node yang akan menjadi child(new node) dengan node saat ini
<br/>![fill](https://user-images.githubusercontent.com/56763570/78790644-ad091c00-7963-11ea-9d03-18929d9df897.PNG)<br/>
##Blank space '0' bergerak ke atas
<br/>![atas](https://user-images.githubusercontent.com/56763570/78789666-4e8f6e00-7962-11ea-9906-31c99b7782a8.PNG)<br/>
##Blank space '0' bergerak ke kiri
<br/>![kiri](https://user-images.githubusercontent.com/56763570/78789693-5818d600-7962-11ea-87ec-4239b4641e5c.PNG)<br/>
##Blank space '0' bergerak ke kanan
<br/>![kanan](https://user-images.githubusercontent.com/56763570/78789702-59e29980-7962-11ea-9a05-f7e051b45bef.PNG)<br/>
##Blank space '0' bergerak ke bawah
<br/>![bawah](https://user-images.githubusercontent.com/56763570/78789705-5bac5d00-7962-11ea-9149-61da117c7512.PNG)<br/>
