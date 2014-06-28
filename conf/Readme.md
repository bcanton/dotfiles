MBP 13.3 with Retina Display
Model No: A1502
Part No: ME865LL/A
Serial No: C02LLA5SFH00
Airport ID: B8:E8:56:41:F3:68
Bluetooth ID: B8:E8:56:41:F3:69


# Textwrangler
mkdir -p ~/"Library/Application Support/TextWrangler/Color Schemes/"
cd ~/Dropbox/conf
cp R.plist ~/Library/Application\ Support/TextWrangler/Language\ Modules
cp Source\ in\ R64.scpt ~/Library/Application\ Support/TextWrangler/Scripts
cp Charcoal\ v1.bbcolor ~/Library/Application\ Support/TextWrangler/Color\ Schemes/
ln -s ~/Library/Application\ Support/TextWrangler/Language\ Modules/R.plist
ln -s ~/Library/Application\ Support/TextWrangler/Scripts/Source\ in\ R64.scpt
ln -s ~/Library/Application\ Support/TextWrangler/Color\ Schemes/Charcoal\ v1.bbcolor
# These require restarts to take effect. Then add a keyboard shortcut via the scripts window

# Terminal Customization
Import Silver\ Aerogel.BC.terminal to Terminal preferences
cd ~/Dropbox/conf
cp .bash_profile ~
ln -s ~/.bash_profile

# Set search domains so you can just type hostnames in terminal
Go to network preferences, DNS, add openvpn explicitly and in the second position add ginkgobioworks.com

# Generate public/private keys 
ssh-keygen

# Enable all possible time machine backups
defaults write com.apple.systempreferences TMShowUnsupportedNetworkVolumes 1
TerribleTwin NAS serial number: 45822771101488
