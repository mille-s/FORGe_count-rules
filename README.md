# FORGe_count-rules

Script to count all rules in FORGe grammars; it provides grammar rule count, submodule rule count, and proportions of language-independent rules.

# Rule and rulesets names specifications
1. Language-specific rules should have a 2-letter prefix indicating the language (e.g. EN_, FR_, etc.). Check that the list of covered languages is correct at the beginning of the script. If a new language is added the code needs to be updated.
2. Ruleset names should start with one or more number(s), with a possible dot in the middle of the number sequence, followed by an underscore (e.g. 10_, 11.1_, etc.).
3. After the numeric prefix, ruleset names should have a module affix among the following: Con_Sem, Sem[^_]*_Sem, Con_Agg[1-9], SemComm_DSynt, DSynt_SSynt, SSynt_PostProc, SSynt_Agg, SSynt_DMorph_linearize, S[mM]orph. If a new module is added the code needs to be updated.

# Instructions for using the script
1. Go to *FORGe_count-rules.ipynb* and open it in Colab.
2. Create a *rule.zip* file that contains the *rule* folder you need the count of. Make sure it only contains grammars that are activated.
3. Upload the *rule.zip* file to the Colab repository (in */content/*, the one you see by default when connecting).
4. Run the first cell of the Colab to unzip the file.
5. Run the second cell of the Colab to run the script.
6. Gather the results in *out.txt*.
