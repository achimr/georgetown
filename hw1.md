The first homework assignment does not involve any programming. Instead,
you will take a closer look at the quality of todays's machine
translation systems.

### Translate a Web Page with Microsoft Translator

1.  Pick a foreign language (preferable one that you have some
    understanding of - or an easy one like French or Spanish); pick a
    language that is supported as a [neural MT language in Microsoft
    Translator](https://www.microsoft.com/en-us/translator/languages.aspx):
    under the heading *Microsoft Translator supported languages* select
    *Neural Translation*
2.  Find a news site that publishes news stories in that language. You
    can also look at Wikipedia articles, if you prefer that.
3.  Pick a web page to translate, select 20 or more sentences and
    translate them with [Microsoft
    Translator](https://translator.microsoft.com/neural/)

### Analyze the Translations

Write a report about the quality of the machine translation.

Go over at least 20 sentences, manually correct each sentence, and
report for each sentence:

1.  the source sentence
2.  the statistical machine translation
3.  the neural machine translation
4.  a correction of the machine translation
5.  an assessment of the error(s) in the statistical machine translation
6.  an assessment of the error(s) in the neural machine translation
7.  whether you picked the statistical or neural translation as the
    better one

You may do steps 5. and 6. in any way you want. For instance, you could
classify errors as "reordering errors", "word sense error for a noun",
or any other type of error you can think of. If you want to, you can
classify the errors using [Multidimensional Quality
Metrics](http://www.qt21.eu/quality-metrics/).

For instance:

1.  *Erst drei Tage ist der neue Ministerpräsident Griechenlands im
    Amt.*
2.  *Only after three days is the new Prime Minister of Greece in the
    Office.*
3.  *It is only three days that the new prime Minister of Greece is in
    office.*
4.  *The new Prime Minister of Greece has been in office for only three
    days.*
5.  Error assessment of the statistical machine translation
    -   The translation says that the minister is in office *after*
        three days, however the source describes the minister being in
        office since three days (MQM accuracy/mistranslation error)
    -   addition of determiner *the* in front of *Office* (MQM
        accuracy/addition error)
    -   the word *Office* is upper case (an MQM fluency/spelling error)
    -   The constituent order, while correct English is awkward. (MQM
        style error)
6.  Error assessment of the statistical machine translation
    -   The word *prime* is lower case (an MQM fluency/spelling error)
7.  neural

Include in your report a summary of your impression of the major quality
problems in the machine translation system that you analyzed.

### What to Hand in

Turn in a written report on Friday, January 26, 2018.
