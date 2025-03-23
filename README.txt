avs2pipemod is a modified version of avs2pipe basically only for my purpose.
Thanks to Chris Beswick who released avs2pipe under GPL 3.

source code : https://github.com/chikuzen/avs2pipemod

Differences with original
* Display total elapsed time.
* contents of 'info'
* New option 'benchmark'.
* New option 'trim'.
* New option 'dumptxt'
* New option 'filters'
* 'y4mp', 'y4mt', 'y4mb' and 'rawvideo' options instead of 'video'.
* FieldBased input will be corrected to framebased on yuv4mpeg2 output modes.
* Colorspace conversion that takes colormatrix and interlace into consideration.
* 'wav', 'extwav' and 'rawaudio' option instead of 'audio'.
* Convert bit depth function in audio output mode.


Usage
	Execute avs2pipemod.exe without any options.
	Then help will be displayed.

Requirements:
	- Avisynth2.6.0final / Avisynth+MT r1706 / Avisynth+ or later.
	- Windows Vista SP2 or later.
	- Microsoft Visual C++ 2015 Redistributable Update 3


                                        written by Oka Motofumi
