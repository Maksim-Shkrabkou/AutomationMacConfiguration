<!-- #Install XCode -->
-> xcode-select --install

<!-- #Install Homebrew -->
-> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
-> brew doctor

<!-- #Install Git -->
-> brew install git
-> git --version
-> git config --global user.name "Name Surname"
-> git config --global user.email johndoe@example.com

<!-- #Configure SSH -->
-> ssh-keygen -t rsa -b 4096
-> pbcopy < ~/.ssh/id_rsa.pub
#add ssh key to Git profile

<!-- #Install htop -->
-> brew install htop
-> sudo htop

<!-- #Install speedtest-cli -->
-> brew install speedtest-cli
-> speedtest-cli

<!-- Install Docker -->
-> Download app from official site 

<!-- #Install ctop (docker container manager) -->
-> brew install ctop

<!-- #Install Postman -->
-> brew cask install postman

<!-- #Install Microsoft Teams -->
-> brew cask install microsoft-teams

<!-- #Install Telegram -->
-> brew cask install telegram

<!-- #Install VS Code -->
-> brew cask install visual-studio-code

<!-- #Install Google Chrome -->
-> brew cask install google-chrome

<!-- #Install dotnet-sdk -->
-> brew cask install dotnet-sdk
-> dotnet --version
-> dotnet --info

<!-- #Install python3 -->
-> brew install python3
-> python3 --version

<!-- #Install SdkMan -->
-> curl -s "https://get.sdkman.io" | bash
<!-- #Follow the instructions on-screen to complete installation.
#Next, open a new terminal or enter: -->
-> source "$HOME/.sdkman/bin/sdkman-init.sh"
-> sdk version

<!-- #Install Java using SdkMan -->
-> sdk install java x.y.z-amzn
<!-- x.y.z-amzn -> version of Java -->

<!-- Install Grandle using SdkMan -->
->  sdk install gradle
<!-- Last stable version -->

<!-- Install iStatMenus -->
-> brew cask install istat-menus

<!-- Install IINA -->
-> brew cask install iina

<!-- Install Kindle -->
-> brew cask install kindle

<!-- Install DaisyDisk -->
-> brew cask install daisydisk

<!-- Enjoy -->