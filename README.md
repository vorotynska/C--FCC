dotnet new console -o /project/guide/

/project/guide/
├── guide.csproj
├── Program.cs
├── obj/
├── bin/



Настройки .gitignore для проекта .NET Console App:

# Скомпилированные файлы
bin/
obj/

# Файлы Visual Studio и Rider
.vscode/
.idea/

# NuGet
*.nupkg
packages/
project.lock.json
project.assets.json
.nuget/