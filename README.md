# Fast Inference in Transformers via speculative decoding

## Run commands
- `translation`
```
    python3 speculative_decoding/translation.py 
        --target_model <large | base | small>
        --small_model  <large | base | small>
        --dynamic_gamma <true | false>
        --heirarchy <true | false>
        --beam_decode <true | false>
```
- `summarization`
```
    python3 speculative_decoding/summarization.py 
        --target_model <large | base | small>
        --small_model  <large | base | small>
        --dynamic_gamma <true | false>
        --heirarchy <true | false>
        --beam_decode <true | false>
```