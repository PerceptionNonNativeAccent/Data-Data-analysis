# Data and Analysis Scripts

--------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: formanti.csv
--------------------------------------------------------------

#	Variable	Explanation

1	  ID	          Unique identified for each target word. 
2	  Stimulus		  Target words with either /ɪ/ or /i/ as syllable nucleus
3   Type          i, i.e. each target word is realized with [ɪ] as syllable nucleus
4   Condition     Binary categorical variable: "canonical" vs. "pseudo": word production with [ɪ] as syllable nucleus either generates the canonical realisation of                   the word, or a pseudoword (i.e., non-canonical)
5   F1            First formant frequencies (Hz)
6   F2            Second formant frequencies (Hz)
7   F3            Third formant frequencies (Hz)

--------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: formantie.csv
--------------------------------------------------------------

#	Variable	Explanation

1	  ID	          Unique identified for each target word. 
2	  Stimulus		  Target words with either /ɪ/ or /i/ as syllable nucleus
3   Type          ie, i.e. each target word is realized with [ɪ] as syllable nucleus
4   Condition     Binary categorical variable: "canonical" vs. "pseudo": word production with [ɪ] as syllable nucleus either generates the canonical realisation of                   the word, or a pseudoword (i.e., non-canonical)
5   F1            First formant frequencies (Hz)
6   F2            Second formant frequencies (Hz)
7   F3            Third formant frequencies (Hz)

--------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: LexDecTask.csv
--------------------------------------------------------------

#	Variable	Explanation

1	  Participant	      Participants ID, which consists of a unique code of two letters and two numbers. 
2	  Item		          The set of stimuli materials used in the LDT, which contains both words and non-words. 
3	  Item_Type         Refers to the four types of target words: (i) target_word_i; (ii) target_word_ie; (iii) filler; (iv) non-word
4	  Correct_Response  Binary Categorical variable: "word" vs. "non-word"
5   Part_Response	    Binary categorical variable: "word" vs. "nonword"
5	  RT_ms		          Time interval in ms between the end of stimulus presentation and participant response
6	  Condition	        Binary categorical variable: "i" vs. "ie". Half of the participants heard all /ɪ/-words in the LDT with an ambiguously produced /ɪ/-vowel,                       while the /i/-words were produced in their canonical, or natural, form (i.e. i-condition). The other half of the participants heard exactly                       the opposite (i.e. ie-condition).
7   Correct           Binary categorical variable: "correct" vs. "incorrect"

--------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: PhonCatTask.csv
--------------------------------------------------------------

#	Variable	Explanation

1	  Participant	      Participants ID, which consists of a unique code of two letters and two numbers. 
2	  Item		          The set of stimuli materials that used in the PCT, i.e. 5 minimal word pairs. 
3	  RT_ms		          Time interval in ms between the end of stimulus presentation and participant response
4   Step              The 4 continuum steps selected from an 11-step continuum ranging between the /ɪ/- and /i/-word of the minimal pair. Selection of these                           steps was based on a pre-test.  
5   Iteration         All 4 steps of the 5 minimal word pairs were repeated 8 times as to enable us to check if responses at the beginning of the PCT differ from                       those towards the end of the PCT.
6   Voice             Binary categorical variable: "female" and "male" voice
7   Condition         Binary categorical variable: "i" vs. "ie". Half of the participants heard all /ɪ/-words in the LDT with an ambiguously produced /ɪ/-vowel,                       while the /i/-words were produced in their canonical, or natural, form (i.e. i-condition). The other half of the participants heard exactly                       the opposite (i.e. ie-condition).
8   Response          Participants' identification of the ambiguous vowel; binary categorical variable: "i" or "ie"
9   VoiceCond         Interaction between (speaker) voice (i.e. "female" vs. "male") and (exposure) condition (i.e. i-ambiguous vs. ie-ambiguous)
