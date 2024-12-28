## RazorPages
## Add Model
- Tạo 1 class Model Movie mới chứa các thông tin
- Tạo folder Pages/Movie.
- Add -> New Scaffolded Item
- using Entity CRUD
- Chọn Model
- Tạo dbContext mới (nút +)
- Được Render các file CRUD (Pages/Movies/CURD) và file DbContext (Data/RazorPagesContext)
## Create Inital Db using EF 
- Tool - Nuget PM - Nuget PM Console
- Add-Migration InitialCreate
- Update-Database
- RazorPagesContext là file được generated db