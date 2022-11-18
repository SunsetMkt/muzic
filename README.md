<br/>
<a href="https://github.com/microsoft/muzic"><img src="img/logo_gradient.png" height="70"> </a>
<br/>
<br/>

**Muzic** is a research project on AI music that empowers music understanding and generation with deep learning and artificial intelligence. 
Muzic is pronounced as [ˈmjuːzeik] and '谬贼客' (in Chinese). Besides the logo in image version (see above), Muzic also has a logo in video version (you can click here to watch <a href="https://ai-muzic.github.io/muzic_logo/"><img src="img/muzic_video_logo.PNG" title="Muzic Video Logo" height="15"/></a>). Muzic was started by [some researchers](https://www.microsoft.com/en-us/research/project/ai-music/) from [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/).  



<!-- [![Muzic Video Logo](img/muzic_video_logo.PNG)](https://ai-muzic.github.io/muzic_logo/ "Muzic Video Logo") -->
  

 

<br/>
We summarize the scope of our Muzic project in the following figure:
<br/><br/>
<p align="center">
<a href="https://github.com/microsoft/muzic">
  <img src="img/concept_map_new.png" height="350"/>
</a>
</p>
<br/>


The current work in [Muzic](https://www.microsoft.com/en-us/research/project/ai-music/) include:
* Music Understanding
  + Symbolic Music Understanding: [MusicBERT](https://arxiv.org/abs/2106.05630)
  + Automatic Lyrics Transcription: [PDAugment](https://arxiv.org/abs/2109.07940) 
* Music Generation
  + Song Writing: [SongMASS](https://arxiv.org/abs/2012.05168)
  + Lyric Generation: [DeepRapper](https://arxiv.org/abs/2107.01875)
  + Lyric-to-Melody Generation: [TeleMelody](https://arxiv.org/abs/2109.09617), [ReLyMe](https://arxiv.org/abs/2207.05688), [Re-creation of Creations (ROC)](https://arxiv.org/abs/2208.05697)
  + Melody Generation: [MeloForm](https://arxiv.org/abs/2208.14345), [Museformer](https://arxiv.org/abs/2210.10349)
  + Accompaniment Generation: [PopMAG](https://arxiv.org/abs/2008.07703)
  + Singing Voice Synthesis: [HiFiSinger](https://arxiv.org/abs/2009.01776)


  You can find some music samples generated by our systems from this page: https://ai-muzic.github.io/.


### We are hiring! 
We are hiring both research FTEs and research interns on **AI music, speech, audio, language, and machine learning**. Please contact Xu Tan (xuta@microsoft.com) if you have interests. 


### What is New!
We give a tutorial on [AI Music Composition](https://www.microsoft.com/en-us/research/uploads/prod/2021/10/Tutorial-on-AI-Music-Composition-@ACM-MM-2021.pdf) at [ACM Multimedia 2021](https://2021.acmmm.org/).

For more speech related research, you can find from this page: https://github.com/microsoft/NeuralSpeech and https://speechresearch.github.io/.



## Requirements

The operating system is Linux. We test on Ubuntu 16.04.6 LTS, CUDA 10, with Python 3.6.12. The requirements for running Muzic are listed in `requirements.txt`. To install the requirements, run:
```bash
pip install -r requirements.txt
```
We release the code of several research work: [MusicBERT](musicbert), [PDAugment](pdaugment), [DeepRapper](deeprapper), [SongMASS](songmass), [TeleMelody](telemelody), [ReLyMe](relyme), [Re-creation of Creations (ROC)](roc), [MeloForm](meloform), and [Museformer](museformer). You can find the README in the corresponding folder for detailed instructions on how to use. 



## Reference

If you find the Muzic project useful in your work, you can cite the following papers if there's a need:

* [1] ***MusicBERT**: Symbolic Music Understanding with Large-Scale Pre-Training*, Mingliang Zeng, Xu Tan, Rui Wang, Zeqian Ju, Tao Qin, Tie-Yan Liu, **ACL 2021**.  
* [2] ***PDAugment**: Data Augmentation by Pitch and Duration Adjustments for Automatic Lyrics Transcription*, Chen Zhang, Jiaxing Yu, Luchin Chang, Xu Tan, Jiawei Chen, Tao Qin, Kejun Zhang, **ISMIR 2022**.
* [3] ***DeepRapper**: Neural Rap Generation with Rhyme and Rhythm Modeling*, Lanqing Xue, Kaitao Song, Duocai Wu, Xu Tan, Nevin L. Zhang, Tao Qin, Wei-Qiang Zhang, Tie-Yan Liu, **ACL 2021**. 
* [4] ***SongMASS**: Automatic Song Writing with Pre-training and Alignment Constraint*, Zhonghao Sheng, Kaitao Song, Xu Tan, Yi Ren, Wei Ye, Shikun Zhang, Tao Qin, **AAAI 2021**.
* [5] ***TeleMelody**: Lyric-to-Melody Generation with a Template-Based Two-Stage Method*, Zeqian Ju, Peiling Lu, Xu Tan, Rui Wang, Chen Zhang, Songruoyao Wu, Kejun Zhang, Xiangyang Li, Tao Qin, Tie-Yan Liu, **EMNLP 2022**.
* [6] ***ReLyMe**: Improving Lyric-to-Melody Generation by Incorporating Lyric-Melody Relationships*, Chen Zhang, LuChin Chang, Songruoyao Wu, Xu Tan, Tao Qin, Tie-Yan Liu, Kejun Zhang, **ACM Multimedia 2022**.
* [7] ***Re-creation of Creations**: A New Paradigm for Lyric-to-Melody Generation*, Ang Lv, Xu Tan, Tao Qin, Tie-Yan Liu, Rui Yan, arXiv 2022. 
* [8] ***MeloForm**: Generating Melody with Musical Form based on Expert Systems and Neural Networks*, Peiling Lu, Xu Tan, Botao Yu, Tao Qin, Sheng Zhao, Tie-Yan Liu, **ISMIR 2022**. 
* [9] ***Museformer**: Transformer with Fine- and Coarse-Grained Attention for Music Generation*, Botao Yu, Peiling Lu, Rui Wang, Wei Hu, Xu Tan, Wei Ye, Shikun Zhang, Tao Qin, Tie-Yan Liu, **NeurIPS 2022**.
* [10] ***PopMAG**: Pop Music Accompaniment Generation*, Yi Ren, Jinzheng He, Xu Tan, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ACM Multimedia 2020**.
* [11] ***HiFiSinger**: Towards High-Fidelity Neural Singing Voice Synthesis*, Jiawei Chen, Xu Tan, Jian Luan, Tao Qin, Tie-Yan Liu, arXiv 2020.


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
