# Effects of Caffeine Intake on Cognitive Performance

## Paper Overview

This GitHub repo contains all files for the paper *Analyzing the Effects of Caffeine on Cognitive Performance*. This study investigates how varying levels of caffeine intake: decaffeinated, regular coffee, and espresso affect attention and mental arithmetic performance. 

The experiment was conducted using the simulation platform *The Island*, with 90 participants evenly assigned to each treatment group. Statistical analysis included summary statistics, visualizations, assumption checks, and non-parametric testing due to violations of ANOVA assumptions.

The methodology and analytical strategies were informed by materials from STA305 at the UTM.

## File Structure

The repo is structured as:

-   `data` contains the cleaned dataset used in this study and the original codebook.
-   `eda` contains the exploratory data analysis (EDA) report in Quarto and PDF formats.
-   `paper` contains the final research paper and supporting Quarto source file.
-   `proposal` contains the initial project proposal and brainstorming document.
-   `llm` contains the whole conversation of LLM usage.

## Key Findings

Key insights from this study suggest that:
- High caffeine intake (espresso) significantly reduces the number of missed letters in an attention test, compared to no caffeine (decaf).
- No significant differences were found in mental arithmetic performance across caffeine intake levels.
- Only the espresso group showed a statistically significant improvement in attention, indicating a possible threshold effect in caffeine's impact.

These findings suggest that caffeine may improve short-term attention but does not significantly affect arithmetic-based reasoning performance.

## License
This project is open-sourced under the MIT license.

## LLM Usage Statement
An LLM, in particular Chat-GPT, was used to aid in the writing of this paper. In particular, it was primarily used to aid with the coding. The entire chat history can be found in `llm/usage.txt`.
