# txt_translation_audio_output
Tool to translate as well generate audio output of translated text, Text content from  English to Indian Languages or Indian Languages to English or Translate from one Indian Language to Another Indian Language directly 


		<< Source file can be || Text or Word or PDF || File >>

1. Download python 3.11.x version

			https://www.python.org/downloads/windows/

			search for 3.11.9 version

2. 

	python3.11 -m venv tts_env
	
	tts_env\Scripts\Activate
	
3.  PIP INSTALL python-docx 
	
	PIP INSTALL PyPDF2
	
	PIP INSTALL gTTS
	
	PIP INSTALL streamlit

		   or 
	
		pip install -r requirements.txt


4. STREAMLIT RUN txt_translation_voice_audio_save file.py

    this will execute the python code


 We can translate from English Text to  => 

		HINDI, TAMIL , TELUGU, KANNADA, MALAYALAM, MARATHI, GUJARATI, BENGALI, URUDU

 We can translate from 

		HINDI, TAMIL , TELUGU, KANNADA, MALAYALAM, MARATHI, GUJARATI, BENGALI, URUDU

		=> English	

 We can translate from any Indian Language Hindi  -> Tamil or Hindi -> Telugu 
 
					   Telugu -> Tamil (Directly)


	From Translated text , we can Generate Audio output and save the audio file as 	.MP3



----------

_langs = {
    "af": "Afrikaans",
    "am": "Amharic",
    "ar": "Arabic",
    "bg": "Bulgarian",
    "bn": "Bengali",
    "bs": "Bosnian",
    "ca": "Catalan",
    "cs": "Czech",
    "cy": "Welsh",
    "da": "Danish",
    "de": "German",
    "el": "Greek",
    "en": "English",
    "es": "Spanish",
    "et": "Estonian",
    "eu": "Basque",
    "fi": "Finnish",
    "fr": "French",
    "fr-CA": "French (Canada)",
    "gl": "Galician",
    "gu": "Gujarati",
    "ha": "Hausa",
    "hi": "Hindi",
    "hr": "Croatian",
    "hu": "Hungarian",
    "id": "Indonesian",
    "is": "Icelandic",
    "it": "Italian",
    "iw": "Hebrew",
    "ja": "Japanese",
    "jw": "Javanese",
    "km": "Khmer",
    "kn": "Kannada",
    "ko": "Korean",
    "la": "Latin",
    "lt": "Lithuanian",
    "lv": "Latvian",
    "ml": "Malayalam",
    "mr": "Marathi",
    "ms": "Malay",
    "my": "Myanmar (Burmese)",
    "ne": "Nepali",
    "nl": "Dutch",
    "no": "Norwegian",
    "pa": "Punjabi (Gurmukhi)",
    "pl": "Polish",
    "pt": "Portuguese (Brazil)",
    "pt-PT": "Portuguese (Portugal)",
    "ro": "Romanian",
    "ru": "Russian",
    "si": "Sinhala",
    "sk": "Slovak",
    "sq": "Albanian",
    "sr": "Serbian",
    "su": "Sundanese",
    "sv": "Swedish",
    "sw": "Swahili",
    "ta": "Tamil",
    "te": "Telugu",
    "th": "Thai",
    "tl": "Filipino",
    "tr": "Turkish",
    "uk": "Ukrainian",
    "ur": "Urdu",
    "vi": "Vietnamese",
    "yue": "Cantonese",
    "zh-CN": "Chinese (Simplified)",
    "zh-TW": "Chinese (Traditional)"
}


