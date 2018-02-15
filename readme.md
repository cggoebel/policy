# policy draft

## Getting Started

### Requirements

+ pandoc

### Generate a docx

    pandoc --toc -V toc-title:"Table of Contents" \
           --template=template.markdown \
           -f markdown+fancy_lists+startnum+definition_lists \
           -o CSDPolicyManual-w-toc.md
           CSDPolicyManual.md
    
    pandoc --template=template.markdown \
           -f markdown+fancy_lists+startnum+definition_lists \
           -o CSDPolicyManual.docx \
           CSDPolicyManual-w-toc.md
