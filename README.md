## meme-cap
This is a repo for the paper: [MemeCap: A Dataset for Captioning and Interpreting Memes](https://arxiv.org/abs/2305.13703)


## Data
[Train+Val](https://github.com/eujhwang/meme-cap/blob/main/data/memes-trainval.json) and [Test](https://github.com/eujhwang/meme-cap/blob/main/data/memes-test.json)

We used 10% of training data as validation data.

Images are available here: [link](https://drive.google.com/file/d/1o1IB6am0HdYS58CEOmmxra3WjJkrn-M1/view?usp=sharing)

## Model
We used [OpenFlamingo-9B](https://github.com/mlfoundations/open_flamingo) and [MiniGPT4](https://github.com/Vision-CAIR/MiniGPT-4) models for our zero-shot and few-shot experiments. 

Check out their code base for the model implementation.


## Paper
If the code is helpful for your project, please cite [our paper](https://arxiv.org/abs/2305.13703) (Bibtex below).
```
@misc{hwang2023memecap,
      title={MemeCap: A Dataset for Captioning and Interpreting Memes}, 
      author={EunJeong Hwang and Vered Shwartz},
      year={2023},
      eprint={2305.13703},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
