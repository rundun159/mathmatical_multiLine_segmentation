<h2> MathMatical MultiLine Segmentation </h2>
<div>
This was developed on C++ using openCV library.
It was developed without using machine learning algorithms.
<br><br>
It consists of three steps.<br>
1. It detects the skewnewss of handwritten lines using huff transform algorithm.  <br>
2. It corrects the skewnewss using OpenCV function. <br>
3. It performs line segmentation following my own algorithm. <br><br>
I implemented this system on my own, and this one works well on recognizing matrix, fraction, limitation, and summation expression as one line, rather than recognizing them as several lines.
</div>
<hr></hr>

# Result
### Multi mathematical lines
<h6>
Image such as below is given. It contains handwritten multi mathematical  lines
</h6>

<img src=./Results/multi_lines.jpg title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

### Segmentation Result

<h6>
The multi lines image is segmented as lines, and images below are returned.
</h6><br/>

#### Line1
<img src=./Results/line1.jpg title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

#### Line2
<img src=./Results/line2.jpg  title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

#### Line3
<img src=./Results/line3.jpg title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

#### Line4
<img src=./Results/line4.jpg  title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

#### Line5
<img src=./Results/line5.jpg  title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

#### Line6
<img src=./Results/line6.jpg  title="TRIM_OFF_cun_waf" alt="TRIM_OFF_cun_waf"></img><br/>

# Algorithm Explanation
<h6>
The algorithm is explained in '/.Algorithm_Explanation/0829_algorithm.pdf'
</h6>
