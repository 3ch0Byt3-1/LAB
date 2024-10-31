<div  align="center"><h1> 💫 LAB: </h1></div>
<br>
<h3> First Go To Kali Linux Offcial Webside -> <a href="https://www.kali.org/get-kali/#kali-platforms">Kali Linux Webside</a> </h3>

-------------------------------------------------------------------------------------
<br>
<h3> Download Torrent File 2024.3 -> <a href="https://cdimage.kali.org/kali-2024.3/kali-linux-2024.3-installer-amd64.iso.torrent">Kali Linux Torrent File</a> </h3>

-------------------------------------------------------------------------------------

<h3> Download qBtorrent 5.00 -> <a href="https://download.fosshub.com/Protected/expiretime=1730010728;badurl=aHR0cHM6Ly93d3cuZm9zc2h1Yi5jb20vcUJpdHRvcnJlbnQuaHRtbA==/38191915f7fd290f36470df7bef0e1a63473b96bf4ad8d5c4cf379bb0dd98eb5/5b8793a7f9ee5a5c3e97a3b2/66f9eecaeeeeed04938b34d1/qbittorrent_5.0.0_x64_setup.exe">qBtorrent</a> </h3>

-------------------------------------------------------------------------------------

<h3> Download Open qBtorrent And Drag Kali Linux Torrent File -> <a href="https://cdimage.kali.org/kali-2024.3/kali-linux-2024.3-installer-amd64.iso.torrent">Kali Linux Torrent File</a> </h3>

-------------------------------------------------------------------------------------
<h3> Download VirtualBox 7.1.4 -> <a href="https://download.virtualbox.org/virtualbox/7.1.4/VirtualBox-7.1.4-165100-Win.exe">VirtualBox</a> </h3>

-------------------------------------------------------------------------------------
<div  align="center"><h1> Install  VirtualBox </h1> </div>
<h3>• Install  VirtualBox 7.1.4 </h3>
<h3>• Open VirtualBox</h3> 

-------------------------------------------------------------------------------------
<div  align="center"><h1> Create  VirtualMachine </h1> </div>
<h3>•  Click Create Button </h3>
<h3>•  File Up The Information's Must add Kali iso </h3> 
<h3>•  Click Create Button </h3>
<h3>•  Click Right Click Kali and Click Settings </h3>
<h3>• Click Network Click NAT To Change To Brige Adapter </h3>
<h3>• Use 2GB Ram And 2-Core Of Ram *Must </h3>

-------------------------------------------------------------------------------------

<div  align="center"> <h1> Power On The Kali And Install it.  </h1> </div>

<br>


<div  align="center"> <h1> Now Upgrade it  </h1> </div>

<h3>•  Command's </h3> 
<h3>

```markdown
sudo apt update && apt upgrade && apt full-upgrade -y
```
</h3>
<h3>

```markdown
reboot
```
</h3>

-------------------------------------------------------------------------------------
<div  align="center"> <h1> Reboot it And Again  </h1> </div>

<h3>•  SSH </h3> 

<h3>

```markdown
sudo apt update && apt upgrade && apt full-upgrade -y
```
</h3>

<h3>

```markdown
sudo apt install openssh-client && systemctl enable ssh.service && systemctl status ssh.service
```
</h3>

-------------------------------------------------------------------------------------
<div  align="center"> <h1> Docker  </h1> </div>

<h3>

```markdown
sudo apt install -y docker.io && sudo systemctl enable docker --now && apt install docker-compose
```
</h3>

-------------------------------------------------------------------------------------
<div  align="center"> <h1> Tools  </h1> </div>
<h3>•  Go </h3> 

<h3>

```markdown
wget https://go.dev/dl/go1.23.2.src.tar.gz && rm -rf /usr/local/go && tar -C /usr/local -xzf go1.23.2.linux-amd64.tar.gz && export PATH=$PATH:/usr/local/go/bin && go version
```
</h3>
<h3>• Sublist3r </h3> 

<h3>

```markdown
sudo apt install sublist3r && sublist3r -h
```
</h3>

<h3>• Subfinder </h3> 

<h3>

```markdown
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
```
</h3>
<h3>• Katana </h3> 

<h3>

```markdown
go install github.com/projectdiscovery/katana/cmd/katana@latest

```
</h3>

<h3>• Nikto </h3> 

<h3>

```markdown
git clone https://github.com/sullo/nikto
cd nikto/program
chmod +x *
./nikto.pl -h http://www.example.com
perl nikto.pl -h http://www.example.com

```
</h3>


<h3>• Nessus </h3> 

<h3>

```markdown
curl --request GET \
  --url 'https://www.tenable.com/downloads/api/v2/pages/nessus/files/Nessus-10.8.3-ubuntu1604_amd64.deb' \
  --output 'Nessus-10.8.3-ubuntu1604_amd64.deb' && dpkg -i Nessus-10.8.3-debian6_amd64.deb
```
</h3>
<!-- <h3>• LAB - EHP </h3>  -->

<h3>
<!-- https://mega.nz/file/saMBmJ6S#R3vl7of5nDAz5Ko9TzRq8756kT5DCgwlpeNAEfrEB4o -->
</h3> 


