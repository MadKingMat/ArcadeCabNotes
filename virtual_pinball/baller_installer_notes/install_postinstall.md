1. Install with baller installer to F:\games\vPinball

2. run c++ runtimes(install_all.bat) from https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/

3. reboot

4. ran option 6 batch in F:\games\vPinball\PinUpSystem\PUPVideos\FP_PE_RETROFLAIR_BAM

5. Updates PinEvent_Settings.vs in F:\Games\vPinball\FuturePinball\Scripts\PinEvent_Settings.vbs:
```
'*** Desktop: Profile 1 ***

If PinEvent_Profile = 1 then
	usePUP 		= true
	usePUP_SSF 	= true
	usePUPDMD 	= true
	usePUP_Stream	= true
	useDOF 		= false
	useFP_Sounds 	= true
	NightModeOption = 1
End if

```
6. Open Table script in Future Pinball and edit script:
```
PinEvent_Profile = 1		'Set what PinEvent Profile you wish to use with this table.
```
