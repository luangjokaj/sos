**Disable the sound effects on boot**
```
sudo nvram SystemAudioVolume=" "
```

**Disable shadow in screenshots**
```
defaults write com.apple.screencapture disable-shadow -bool true
```

**Set a blazingly fast keyboard repeat rate**
```
defaults write NSGlobalDomain KeyRepeat -int 1
defaults write NSGlobalDomain InitialKeyRepeat -int 10
```

**Add iOS & Watch Simulator to Launchpad**
```
sudo ln -sf "/Applications/Xcode.app/Contents/Developer/Applications/Simulator.app" "/Applications/Simulator.app"
sudo ln -sf "/Applications/Xcode.app/Contents/Developer/Applications/Simulator (Watch).app" "/Applications/Simulator (Watch).app"
```

**Privacy: don’t send search queries to Apple**
```
defaults write com.apple.Safari UniversalSearchEnabled -bool false
defaults write com.apple.Safari SuppressSearchSuggestions -bool true
```
**`/etc/hosts`**
```
##
# Host Database
#
# localhost is used to configure the loopback interface
# when the system is booting.  Do not change this entry.
##
127.0.0.1		localhost
255.255.255.255	broadcasthost
::1				localhost
127.0.0.1		blog.ps-prod.local
127.0.0.1		holcim.ps-prod.local
127.0.0.1		medinisde.localhost
127.0.0.1		medinside.ps-prod.local
127.0.0.1		peerworld.ps-prod.local
127.0.0.1		wiki.ps-prod.local
127.0.0.1		witzig.ps-prod.local
127.0.0.1		yio.ps-prod.local
127.0.0.1		volkswagen2019.spectra.local
127.0.0.1		adeccospring.spectra.local
127.0.0.1		amag-autorama.spectra.local
127.0.0.1		amag-autowelt.spectra.local
127.0.0.1		amag-deepimpact.spectra.local
127.0.0.1		amag-von-kaenel.spectra.local
127.0.0.1		amag.spectra.local
127.0.0.1		amagadmin.spectra.local
127.0.0.1		amagauth.spectra.local
127.0.0.1		boilerplate.spectra.local
127.0.0.1		community.spectra.local
127.0.0.1		dealersites.spectra.local
127.0.0.1		dealestate.spectra.local
127.0.0.1		di.spectra.local
127.0.0.1		holcimpartnernet.spectra.local
127.0.0.1		hpn-ch.spectra.local
127.0.0.1		hpn-sge.spectra.local
127.0.0.1		hpn.spectra.local
127.0.0.1		kartause.spectra.local
127.0.0.1		mobileid.spectra.local
127.0.0.1		mobileid18.spectra.local
127.0.0.1		mobileid19.spectra.local
127.0.0.1		seat-store.spectra.local
127.0.0.1		seat.spectra.local
127.0.0.1		skoda.spectra.local
127.0.0.1		sps-annualreport2017.spectra.local
127.0.0.1		sps-ecommunity.spectra.local
127.0.0.1		spsswiss2-immobilien.spectra.local
127.0.0.1		spsswiss2.immobilien.spectra.local
127.0.0.1		spsswiss2.spectra.local
127.0.0.1		stadttheater-langenthal.spectra.local
127.0.0.1		swissprimesite.spectra.local
127.0.0.1		volkswagen-nutzfahrzeuge.spectra.local
127.0.0.1		volkswagen-nutzfahrzeuge2019.spectra.local
127.0.0.1		audi.spectra.local
127.0.0.1		mobimo.spectra.local
127.0.0.1		amag-baschnagel.spectra.local
127.0.0.1		amag-ticino.spectra.local
127.0.0.1		amagemotiondays.spectra.local
127.0.0.1		amag-amag-ebikon.spectra.local
127.0.0.1		amag-amag-etoy.spectra.local
127.0.0.1		local.skyfonts.com
127.0.0.1		wordpressify.local
127.0.0.1		volkswagen.spectra.local
127.0.0.1		varese.spectra.local
127.0.0.1		varese-ch.spectra.local
127.0.0.1		varese-de.spectra.local
127.0.0.1		seat2019.spectra.local
127.0.0.1		seat-store2019.spectra.local
127.0.0.1		figmadaemon.com
127.0.0.1		holcim.localhost
0.0.0.0			account.jetbrains.com
0.0.0.0			smiling-fish
0.0.0.0			ramus
0.0.0.0			rele
0.0.0.0			rele.dev
0.0.0.0			tenti-webshop
0.0.0.0			frutico.local
0.0.0.0			shop.frutico.local
0.0.0.0			videojobs
```