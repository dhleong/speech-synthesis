# speech-synthesis

Library to speak text.

# Usage

Add this to your project.clj:
   
    [org.clojars.dhleong/speech-synthesis "1.0.1"]

Add to your ns:

    (:use [speech-synthesis.say :as say])

Turn speech to text:

    (say/say)
