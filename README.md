# GPT2 My little pony

[![Run on Ainize](https://ainize.ai/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/fpem123/GPT2-MyLittlePony)

This project generate My little pony script using GPT-2 model.

Fine tuning data: [Kaggle](https://www.kaggle.com/liury123/my-little-pony-transcript?select=clean_dialog.csv)

Model download: [Google drive](https://drive.google.com/file/d/1-B5sWk614-dWMj4NcAPIIWVsATLnNwRq/view?usp=sharing)

### Model information

    Base model: gpt-2 large
    Epoch: 30
    Train runtime: 4943.9641 secs
    Loss: 0.0291

### How to use

    * First, Choose My little pony character name.
    * Second, Fill what the character will say in text. This will be base of script.
    * And then, Fill number in length. Text is created as long as "length". I recommend between 100 and 300.
    * If length is so big, generate time will be long.

### Post parameter

    name: The My little pony character name.
    text: The base of script.
    length: The size of generated text.


## * With CLI *

    curl -X POST "https://master-gpt2-my-little-pony-fpem123.endpoint.ainize.ai/mlp" -H "accept: application/json" -H "Content-Type: multipart/form-data" -F "name=Twilight Sparkle" -F "text=Hello everyone" -F "length=150"

## * With swagger *

API page: [In Ainize](https://ainize.ai/fpem123/GPT2-MyLittlePony?branch=master)

## * With a Demo *

Demo page: [End-point](https://master-gpt2-my-little-pony-fpem123.endpoint.ainize.ai/)
