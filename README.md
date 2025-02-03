---

![image](https://github.com/user-attachments/assets/f074e55a-2745-450a-b49d-d3910a076e29)

## 📌 For a detailed guide with images, visit:
[Full Installation Guide with Images](https://docs.google.com/document/d/1lAAB4vIwGqfSxhT8_EPQWEeyoIzXy3rArp5aDYNlW3c/edit?usp=sharing)  

## 📌 Refer to the official Laravel documentation: 
[Laravel Docs](https://laravel.com/docs/)  

---

# Laravel Installation Guide (Any Latest Version)  

## Introduction  
This guide provides a step-by-step process to set up **any latest Laravel version** using only three essential tools: **XAMPP, Composer, and Visual Studio Code**. It is designed for beginners and developers who want a quick and easy installation without unnecessary complexity. By following this guide, you will be able to set up a Laravel environment on your local machine and start building your applications in no time.  

## Prerequisites  
Ensure you have the following installed:  
- **XAMPP** (PHP 8.2.12) → [Download](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/8.2.12/xampp-windows-x64-8.2.12-0-VS16-installer.exe)  
- **Composer** (v2.8.5) → [Download](https://getcomposer.org/Composer-Setup.exe)  
- **Visual Studio Code** (v1.96.4) → [Download](https://code.visualstudio.com/)  

## Installation Steps  

### 1. Install XAMPP  
- Run the downloaded installer and follow the on-screen instructions.  
- Allow the firewall prompt and finish the installation.  
- Open **XAMPP Control Panel**, start **Apache & MySQL**.  

### 2. Install Composer  
- Run the installer and select **"Install for all users"**.  
- Ensure the PHP path is added automatically.  
- Complete the installation.  

### 3. Install Visual Studio Code  
- Run the installer and accept the license agreement.  
- Follow the steps and complete the installation.  

## Creating Your First Laravel Project  

1. Open **XAMPP Control Panel**, click "Config" on **Apache**, open `php.ini`, and enable `extension=zip`.  
2. Open **VS Code**, launch the terminal, and navigate to `C:\`:  
   ```sh
   cd\
   mkdir laravel
   cd laravel
   ```
3. Install Laravel globally:  
   ```sh
   composer global require laravel/installer
   ```
4. Create a new Laravel project:  
   ```sh
   laravel new first-project
   ```
5. Follow prompts to set up the database (MySQL recommended).  
6. Navigate into your project folder:  
   ```sh
   cd first-project
   composer self-update
   composer update
   ```
7. Run the project:  
   ```sh
   php artisan serve
   ```
8. Open `http://127.0.0.1:8000` in a browser.  

---
