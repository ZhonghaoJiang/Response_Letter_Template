# Response Letter Template for TSE/TOSEM

This repository contains a LaTeX template for writing response letters to reviewers and editors of TSE/TOSEM journals (maybe others). 
The template is designed to help authors effectively address the comments and suggestions provided by reviewers and editors during the peer review process.

## Usage

### Basic Info Setting

In the `main.tex` file, set the basic information such as the title of the response letter, authors, and date.

```latex
\manuscriptid{TSE-2024-xx-xxxx}
\manuscripttitle{xxxxx}
```

### Editor Comments and Responses

In the `editor.tex` file, add the comments from the editor and your responses. 
Use the `\editorComment{}` command for editor comments and `\response{}` command for your responses.

```latex
\editorComment{
    xxx
}

\response{
    Thank you for the advice. We have already revised our manuscript based on reviewers’ helpful comments.
}
```

### Reviewer Comments and Responses
In the `R1.tex`, `R2.tex`, and `R3.tex` files, add the comments from each reviewer and your responses. 
Use the `\reviewerComment{}` command for reviewer comments and `\response{}` command for your responses.

A full response to a comment may be shown as follows:
```latex
\reviewerComment{
    xxx
}

\response{
    xxx
}
    
\referencesContent{
    [1] xxx.
}
    
\action{
    We have xxx. \textbf{(Lines xx-xx)}
        
    \oriContent{
        xxxx
    }
}
```
