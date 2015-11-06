PIX/Boom Recorder Controller
v1.0



This script serves to synchronize transport and metadata across Boom Recorder and Sound Devices rack recorders (PIX 260i, PIX270i, SD970), using Boom Recorder's AppleScript functionality and PIXNET as a backend. 

As of the time of writing, transport control flows in either direction whereas boom recorder acts as a master for metadata, writing to the PIX. The script also handles boom recorder's take incrementing, synching it automatically to the take of the PIX upon ending a recording. As such...




		############################################

		Please ensure that 'Increment 'Take' after 
		recording' is unchecked in Boom Recorder 
		Metadata settings.
		############################################




Will Colding
Gotham Sound and Communications
willc@gothamsound.com
11/6/2015