

<h2>Information</h2>

<p>Yan Gong<br/>Autonomous Driving | Multimodal Fusion | Thermal Image<br/>School of Vehicle and Mobility, Tsinghua University, China (Research Assistant) <br/>School of Computer Science and Engineering, Northeastern University, China (Postgraduate Student)<br/>Email: gongyan2020@foxmail.com / gongyan1998@gmail.com  </p>

<hr/>

<h3>Publication</h3>

<ol>
  
  <li>Multi-Modal Attention Guided Real-Time Lane Detection<br/> 
    Xinyu Zhang*, <b>Yan Gong</b> (Co-first author), Zhiwei Li, Xuan Liu, Yiqian Lu and Jun Li<br/>
    IEEE International Conference on Advanced Robotics and Mechatronics (ICARM), 2020, Accepted, Best paper<br/>
    Contribution: Idea, Code, Paper
  </li>
  <a href="https://ieeexplore.ieee.org/document/9536157" class="aaa">PDF</a>  <a href="" class="aaa">Code</a> <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: Multimodal data fusion is becoming a trend for the field of autonomous driving, especially for lane detection. In the process of driving, sensors often encounter problems such as modality imbalance, changing illumination and so on. Therefore, it is worthwhile to study the problems of applying multimodal fusion for lane detection and modality imbalance in the fusion process. In this paper, we propose a novel multimodal model for lane detection, in which attention mechanism is embedded into network to balance multimodal feature fusion and to improve detection capability. In addition, we use multi-frame input and long short-term memory (LSTM) network to solve the shadow interference, vehicles occlusion and mark degradation. At the same time, the network can be applied to the task of lane detection. In order to verify the effect of multimodal application and attention mechanism on fusion, we have designed adequate experiments on processed continuous scene KITTI dataset. The results show that precision increases by about 15% when LiDAR is added compared with RGB only. Besides, attention mechanism obviously improves the performance of multi-modal detection by balancing multi-modal features.</div>
  
  
  <li>An Open Multimodal Perception Dataset For Autonomous Driving<br/> 
    Xinyu Zhang, Zhiwei Li*, <b>Yan Gong</b>(Co-first author), Dafeng Jin, Jun Li, Li Wang, Yanzhang Zhu and Huaping Liu <br/> 
    IEEE Transactions on Vehicular Technology, 2021, Accepted<br/> 
    Contribution: Idea, Code, Paper
  </li>
  <a href="" class="aaa">PDF</a>  <a href="" class="aaa">Code</a>   <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: Multi-modal sensor fusion techniques have promoted the development of autonomous driving, while perception in the complex environment remains a challenging problem. In order to tackle the problem, we propose the Open Multi-modal Perception dataset (OpenMPD), a multi-modal perception benchmark objected at difficult examples. Compared with existing datasets, OpenMPD focuses more on those complex traffic scenes in urban areas with overexposure or darkness, crowded environment, unstructured roads and intersections. It acquires the multi-modal data through a vehicle with six cameras and four LiDAR for a 360-degree field of view and collected 180 clips of 20-second synchronized images at 20Hz and point clouds at 10Hz. Particularly, we applied a 128-beam LiDAR to provide Hi-Res point clouds to better understand the 3D environment and sensor fusion. We sampled 15K keyframes at equal intervals from clips for annotations, including 2D/3D object detections, 3D object tracking, and 2D semantic segmentation. Moreover, we provide four benchmarks for all tasks to evaluate algorithms and conduct extensive experiments of 2D/3D detection and segmentation on OpenMPD. Data and further information are available at http://www.openmpd.com/.</div>
  
  
   <li>Channel Attention in LiDAR-camera Fusion for Lane Line Segmentation<br/> 
    Xinyu Zhang, ZhiweiLi, Xin Gao, Dafeng Jin, Jun Li<br/> 
    Pattern Recognition, 2021, Accepted<br/> 
    Contribution: Code
  </li>
  <a href="https://www.sciencedirect.com/science/article/pii/S0031320321002077" class="aaa">PDF</a>  <a href="" class="aaa">Code</a>   <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: To assess the contributions of the different feature channels of sensors, we introduce a novel multimodal fusion method and demonstrate its practical utility using LiDAR-camera fusion networks. Specifically, a channel attention module that can be easily added to a fusion segmentation network is proposed. In this module, we use the channel attention mechanism to obtain the cross-channel local interaction information, and the weights of feature channels are assigned to represent the contributions of different feature channels. To verify the effectiveness of the proposed method, we conduct experiments on two types of feature fusion with the KITTI benchmark and A2D2 dataset. Our model achieves precise edge segmentation, with a 5.59% gain in precision and a 2.12% gain in F2-score compared to the values of the original fusion method. We believe that we have introduced a new optimization idea for multimodal fusion.</div>
  
  
  
  <li>SkipCrossNets: Adaptive Fusion for road detection<br/> 
    Zhiwei Li, <b>Yan Gong</b>(Co-first author), Xinyu Zhang*, Zhenhong Zou, Dafeng Jin and Jun Li <br/> 
    IEEE Transactions on Intelligent Transportation Systems, 2021, Under Second Review<br/> 
    Contribution: Idea, Code, Paper
  </li>
  <a href="" class="aaa">PDF</a>  <a href="" class="aaa">Code</a>   <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: There has been an increasing awareness in leveraging multi-modal fusion in autonomous driving tasks like road detection, while optimal fusion architecture remains unknown. We propose a novel fusion network named skip-cross networks (SkipcrossNets) that combines LiDAR point clouds and camera images adaptively. We argue the two modalities provide different level of information in feature extraction. Therefore, the fusion network will benefit from our feature matching. Specifically, the proposed skip-cross structure allows the network to select the most similar feature layers from two data pipelines for fusion. Moreover, we divide the network into several blocks to reduce the complexity of feature selection and parameters of models. We demonstrate the advantage of skip-cross fusion strategy, by evaluating it on the KITTI and A2D2 datasets. We achieve the MaxF score of 96.85% on KITTI and the F1 score of 84.84% on A2D2. Meanwhile, our model parameters are only 2.33 MB and the speed is 68.24 FPS, which has great potential in mobile terminal and embedded devices.</div>
  
  
   <li>Vibration: Another vital Factor in Lane Detection<br/> 
    Zhiwei Li, <b>Yan Gong</b>(Co-first author)</b>, Xinyu Zhang, Liangyu Wang, Jun Li and Hao Shen<br/> 
    IEEE International Conference on Robotics and Automation (ICRA), 2021, Under Review<br/> 
    Contribution: Idea, Code, Paper
  </li>
  <a href="" class="aaa">PDF</a>  <a href="" class="aaa">Code</a>   <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: Lane detection plays an important role in autonomous driving. Nowadays, many lane detection tasks have achieved remarkable performance and got excellent results. However, most of the lane detection models cannot deal with extreme weather such as heavy fog and heavy rain, nor can they deal with lane detection task in the scene of changing lanes. In this work, we first proposed a fusion strategy that combines vibration signals and images.
Our work provides new ideas for lane detection in extreme weather conditions like fog and rain since the vibration signal on lane is less likely to be influenced by them, also for the lane detection task in changing lanes scene. We use our fusion strategy to improved performance of lane detection model based on semantic segmentation, and propose <i>VBLaneNet: The vibration-based lane detection network</i>. The model was evaluated on our own dataset <i>VBLane: The vibration-based dataset for lane detection</i>, which contains both vibration signals and visual images. The results(recall(96.29%), F1(95.43%), mIOU(91.38%)) show that our model outperforms the current state-of-the-art lane detection methods based on semantic segmentation. Compared with our baseline, our strategy performs better in the detection of lane line pixels and has almost no effect on the speed of the model(only about 3 FPS slower), which also verifies that our method is easy to use and deployable.</div>
  
  
 <li>A Feature Aggregation Network for Multispectral Pedestrian Detection<br/> 
    <b>Yan Gong</b>, Lu Wang* and Lisheng Xu
    Applied Intelligence, 2021, Under Review<br/> 
    Contribution: Idea, Code, Paper
  </li>
  <a href="" class="aaa">PDF</a>  <a href="" class="aaa">Code</a>   <button class="button">More details</button>  
    <div class="hidden paper_d" style="display:none"> Abstract: Pedestrian detection is an important task in many computer vision applications. Since multispectral pedestrian detection can alleviate the difficulties of insufficient illumination at night, it has been rapidly developed in recent years. However, the way for effective color-thermal image fusion still needs further research. In this paper, we propose a Feature Aggregation Module (FAM) that can adaptively capture the cross-channel and cross-dimensional information interaction of the two modalities. In addition, we develop a Feature Aggregation Network (FANet) that embeds the proposed FAM module into a two-stream network adapted from the YOLOv5. The FANet has the advantages that its size is small (15 MB) and it runs fast (8 ms per frame). Extensive experiments on the KAIST dataset show that the proposed method is effective for multispectral pedestrian detection, especially in the nighttime condition, for which the Miss Rate is only 8.91%. Moreover, we show that the saliency map computed from the thermal image can be incorporated into the FANet to further increase the detection accuracy. In order to verify the generalization ability of the FAM module, we have also conducted experiments on the person re-identification datasets, namely Market1501 and Duke. The performance of our FAM compares favorably against existing feature fusion mechanisms on the two datasets.</div>
  

  
  

</ol>

<hr/>

<h3>Patent</h3>

<ol>
  
  <li>
    A lane detection method and terminal equipment based on attention mechanism. <br/>
    CN111950467A, 2020, Accepted<br/>
    Xxinyu Zhang, Zhiwei Li, Jun Li, <b>Yan Gong</b>, Xin Gao and Huaping Liu
  </li>
  
  <li>
    A method for detecting and identifying the wearing condition of labor insurance products based on deep learning.<br/>
    CN202010197049.6, 2020, Under review <br/>
    Yudong Liang, Yixiong Ning, <b>Yan Gong</b>, Jinhao Xie, Chao Zhang and Deyu Li
  </li>

</ol>

<hr/>

<h3>Experience </h3>

<table>
    <tr>
      <th>Time</th>
      <th>Institution</th>
      <th>Position</th>
      <th>Description</th>
    </tr>
    <tr>
      <td>2020.4~Now</td>
      <td>School of Vehicle and Mobility, Tsinghua University </td>
      <td>Research Assistant</td>
      <td><button class="button">Show</button></td>
    </tr>
    <tr>
        <td class = "hidden fused_td" colspan="4" style="display:none"> 
            Extensive experiments on the KAIST dataset show that the proposed method is effective for multispectral pedestrian detection, especially in the nighttime condition
        </td>
    </tr>
    <tr>
        <td>2021.7~2021.11</td>
        <td>AI Research Institute, Jingdong </td>
        <td>Algorithm engineer </td>
        <td><button class="button">Show</button></td>
    </tr>
    <tr>
        <td class = "hidden fused_td" colspan="4" style="display:none"> 
            Extensive experiments on the KAIST dataset show that the proposed method is effective for multispectral pedestrian detection, especially in the nighttime condition
        </td>
    </tr>
    <tr>
        <td>2021.11~2022.1</td>
        <td>Algorithm Development Product Department, Megvii</td>
        <td>Algorithm engineer </td>
        <td><button class="button">Show</button></td>
    </tr>
    <tr>
        <td class = "hidden fused_td" colspan="4" style="display:none"> 
            Extensive experiments on the KAIST dataset show that the proposed method is effective for multispectral pedestrian detection, especially in the nighttime condition.
        </td>
    </tr>
</table>

<hr/>

<h3>Honor</h3>

<hr/>

<h3>Skill</h3>

<p>Language: Chinese, English<br/>Programming: Python, MATLAB, C++, HTML<br/>Tools: PyTorch, TensorRT, OpenCV, PCL, LaTeX, Markdown, Git  </p>

<hr/>


<script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
<script type="text/javascript">

  

button_list = $(".button")
hidden_div = $(".hidden")
len = button_list.length
var arr = new Array(len).fill(0)

button_list.each(function(i,e){
    $(e).click(function(){
    hidden_div.eq(i).show()
    arr[i] = arr[i]+1
    if (arr[i]%2!=0){
        hidden_div.eq(i).show()
    } else {
        hidden_div.eq(i).hide()
    }
})
})
  
</script>
