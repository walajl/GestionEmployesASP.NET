# 🏢 GestionEmployees - Application de Gestion des Employés

Application web de gestion des employés développée avec ASP.NET Core 8.0 et Entity Framework.

## 📱 Fonctionnalités

### Pour la Gestion des Employés
- ➕ Ajout d'un nouvel employé avec formulaire validé
- 📋 Consultation de la liste des employés
- ✏️ Modification des informations d'un employé
- 🗑️ Suppression d'un employé avec confirmation
- 🔍 Recherche par nom d'employé
- 🏷️ Filtrage par département avec Spinner

### Pour le Tableau de Bord
- 📊 Affichage du nombre total d'employés
- 👤 Dernier employé ajouté
- 📅 Date du jour

## 🛠️ Technologies Utilisées
- Langage : C#
- IDE : Visual Studio 2022
- Framework : ASP.NET Core 8.0
- Pages : Razor Pages
- Base de données : SQL Server LocalDB
- ORM : Entity Framework Core 8.0
- Frontend : Bootstrap 5
- Icônes : Bootstrap Icons

## 📂 Structure du Projet
```
GestionEmployees/
├── Data/
│   └── GestionEmployeesContext.cs
├── Models/
│   ├── Employee.cs
│   └── SeedData.cs
├── Migrations/
│   └── ...
├── Pages/
│   ├── Employees/
│   │   ├── Index.cshtml
│   │   ├── Create.cshtml
│   │   ├── Edit.cshtml
│   │   ├── Details.cshtml
│   │   └── Delete.cshtml
│   ├── Shared/
│   │   └── _Layout.cshtml
│   ├── Index.cshtml
│   ├── Privacy.cshtml
│   └── Contact.cshtml
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
├── Program.cs
└── appsettings.json
```

## 🚀 Installation

1. **Cloner le repository**
```bash
git clone https://github.com/walajl/CRUD-ASP.NET.git
```

2. **Ouvrir dans Visual Studio**
- File > Open > Sélectionner le dossier du projet

3. **Restaurer les packages**
```bash
dotnet restore
```

4. **Appliquer les migrations**
```bash
dotnet ef database update
```

5. **Compiler et exécuter**
```bash
dotnet run
```

## 👥 Auteur
- **Walaeddine Jlassi** - Développeur

## 📄 Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.
