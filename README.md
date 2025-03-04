[comment]: <> (# event_flow)

<h1 align="center"> SNN-based event_flow (中文注释版~仅供个人学习记录用)
</h1>

[comment]: <> ( <h2 align="center">PAPER</h2>)
  <h3 align="center">
  <a href="https://proceedings.neurips.cc/paper_files/paper/2021/file/39d4b545fb02556829aab1db805021c3-Paper.pdf" target="_blank">Paper</a>
  | <a href="https://github.com/tudelft/event_flow" target="_blank">Original Github Page</a>
  | <a href="https://kwanwaipang.github.io/Awesome-Event-based-Contrast-Maximization/" target="_blank">Blog for CM</a>
  </h3>
  <div align="center"></div>

<!-- rm -rf .git -->

训练代码，可以用ANN或者SNN
~~~
python train_flow.py --config configs/train_ANN.yml
python train_flow.py --config configs/train_SNN.yml
~~~

相比起[ssl_e2vid](https://github.com/KwanWaiPang/ssl_e2vid_comment)loss变化是比较多的，但是从实验效果来看，好像提升不大~
虽然论文的附录A验证了`Convexity of the self-supervised loss function`，但是只是可视化，没有数值指标~~~
