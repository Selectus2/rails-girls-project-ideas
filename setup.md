## Installation Guide  

### Windows  

#### Install Ruby  
1. Download the [RubyInstaller](https://rubyinstaller.org/2023/04/01/rubyinstaller-3.2.2-1-3.1.4-1-3.0.6-1-and-2.7.8-1-released.html) for Windows.  
2. Install Ruby version **3.2.x** (32-bit).  
3. Run the installer and proceed with the default options.  
4. Ensure the **“Run ‘ridk install’”** checkbox is selected during installation.  
5. When prompted by the **MSYS2** installer:  
   - Enter **1** and press **Enter** when asked the first time.  
   - Press **Enter** when asked again.  

#### Install Rails  
1. Open **Command Prompt** and run:  
   ```sh
   gem install rails bundler --no-document
   ```  
2. Verify the installation by checking the Rails version:  
   ```sh
   rails --version
   ```  

### Ubuntu  

```sh
sudo apt-get update
sudo apt install ruby-full -y
gem install rails -v 7.2.0
```  

### macOS  

```sh
brew install ruby
gem install rails -v 7.2.0
```  

### Verify Installation  

1. Create a new Rails application:  
   ```sh
   rails new myapp
   ```  
2. Navigate into the app directory:  
   ```sh
   cd myapp
   ```  
3. Start the Rails server:  
   ```sh
   rails server
   ```  
4. Open your browser and visit: **http://localhost:3000**  
   - You should see the Rails logo confirming a successful installation.

