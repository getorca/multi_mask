# multi mask - uncover multiple masked tokens in the middle of text

A simple demo uncovering multiple masked tokens in the middle of a sentence with roberta. 

Insipered by: <https://ramsrigoutham.medium.com/sized-fill-in-the-blank-or-multi-mask-filling-with-roberta-and-huggingface-transformers-58eb9e7fb0c>

## Issues
- need to know the numebr of tokens to unmaks
- is it that useful?

## Going further
- Could potentially train up to a masked token length, and pad out the blank tokens with `unk` or `pad` token

