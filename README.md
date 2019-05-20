# My 100 Days of Code Journey

**Starting date**: 2019/05/19

**Themes**: opendata, machine learning, NLP 
## Plans
1. [Siam-IPA][siam-ipa]: ซึ่ง คือ Homebrew tap ที่รวม libraries และ MacOS applications สำหรับคนไทย ตอนนี้ มี 2 Formulas คือ
    1. Thai-Eng Dict
    2. 13 ฟอนต์แห่งชาติจาก SIPA 
    
    **โดยสิ่งที่อยากทำเพิ่มคือ** เพิ่ม Fomula ของ Thai fonts จาก [f0nt.com](http://f0nt.com) และ Formula สำหรับ SWATH ซึ่งเป็น library ที่ใช้สำหรับตัดคำภาษาไทย

2. [Databuri][databuri]: ตัวโปรเจ็คนี้จะเป็น Python Package ที่รวม datasets ที่เกี่ยวข้องกับประเทศไทย ไว้ในที่เดียวกัน และเป็น Proxy สำหรับ APIs ต่างๆ ที่ทางภาครัฐมี 
3. Hanuman: อีกโปรเจ็คที่อยากทำคือ Python Package ที่ใช้สำหรับ run command ตาม template เช่น เรามี parameters คือ `algorithm={ fast_alg, slow_alg }` กับ `dataset={ big, small}`
แล้วอยากรันคำสั่ง `train.py -a <ALG> -d <DATASET>` ของ ทุก algorithm x dataset 

    ซึ่งเบื้องต้นคิดว่า ตัว command template, parameters จะอยู่ใน config file แล้วเรียนผ่าน 
    ```
        hanuman --config something.yml
    ```
4. Contributions to PyThaiNLP and other ML projects.
    - Current WIP: https://github.com/PyThaiNLP/pythainlp-webdemo/pull/3
    - Dataset เกี่ยวกับ ดูดวง เผื่อทำ conditional text generation
    - Wisesight sentiment analysis with explainable prediction
    - ... 
        

## Expectation
TBD.

## Log

[siam-ipa]: https://github.com/codeforthailand/homebrew-siam-ipa
[databuri]: https://github.com/codeforthailand/databuri
