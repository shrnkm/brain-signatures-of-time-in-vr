### **Supplementary Materials**
# **Brain Signatures of Time Perception in Virtual Reality**

<h3>
  <a href="https://orcid.org/0000-0002-8021-1021" target="_blank">Sahar Niknam</a>, 
  <a href="https://orcid.org/0000-0002-8691-4991" target="_blank">Saravanakumar Duraisamy</a>, 
  <a href="https://orcid.org/0000-0001-8492-7708" target="_blank">Jean Botev</a>, 
  <a href="https://orcid.org/0000-0002-5011-1847" target="_blank">Luis A. Leiva</a>
</h3>

<p>
  <a href="https://vrarlab.uni.lu" target="_blank">VR/AR Lab</a> & 
  <a href="https://www.uni.lu/fstm-en/research-groups/computational-interaction/" target="_blank">COIN Lab</a>, 
  @<a href="https://www.uni.lu/en/" target="_blank">University of Luxembourg</a>
</p>



------------------------------------------------------------------------

## **1. Study Setup**
<table>
  <tr>
    <td colspan="4"><img src="images/study_setup_01.jpg" alt="study setup" width="100%"></td>
    <td colspan="2"><img src="images/study_setup_02.jpg" alt="study setup" width="100%"></td>
  </tr>
  <tr>
    <td colspan="6" align="center"><img src="images/study_setup_03.jpg" alt="used devices" width="100%"></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/Unicorn.png" alt="EEG cap" width="100%"></td>
    <td colspan="2"><img src="images/Leap.png" alt="Handtracker" width="100%"></td>
    <td colspan="2"><img src="images/HTC.png" alt="VR headset" width="100%"></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <a href="https://www.unicorn-bi.com/" target="_blank" style="text-decoration: underline; color: #0077b6;">
        Unicorn Hybrid Black EEG cap
      </a>
    </td>
    <td colspan="2" align="center">
      <a href="https://www.ultraleap.com/product/" target="_blank" style="text-decoration: underline; color: #0077b6;">
        Leap Motion Controller
      </a>
    </td>
    <td colspan="2" align="center">
      <a href="https://business.vive.com/sea/product/vive-pro-eye/" target="_blank" style="text-decoration: underline; color: #0077b6;">
        HTC Vive Pro Eye VR headset
      </a>
    </td>
  </tr>
</table>

------------------------------------------------------------------------

## **2. Precedure**
<div style="text-align: center;">
  <img src="images/procedure.png" alt="experiment procedure" style="width: 80%; height: auto; margin: auto;">
  
  <video id="video-player" controls style="width: 100%; height: auto; margin: 10px 0;">
    <source src="videos/procedure.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <p>An example of an event: Cognitive modulator, Medium mode, duration 6 seconds</p>
</div>

------------------------------------------------------------------------

## **3. Modulators**
<img src="images/events.png" alt="5 modulators to 42 events" style="width: 100%; height: auto;">

### 3.1. Emotion
<table>
  <caption>Valence and arousal values of pictures used for implementing the emotion modulator<br></caption>
  <thead>
    <tr>
      <th>Mode</th>
      <th></th>
      <th>Picture 1</th>
      <th>Picture 2</th>
      <th>Picture 3</th>
      <th>Picture 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><b>Positive<br>High</b></td>
      <td>Valence</td>
      <td>91.266†</td>
      <td>81.696†</td>
      <td>6.67</td>
      <td>6.50</td>
    </tr>
    <tr>
      <td>Arousal</td>
      <td>57.636†</td>
      <td>66.009†</td>
      <td>4.04</td>
      <td>3.08</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Positive<br>Low</b></td>
      <td>Valence</td>
      <td>94.105†</td>
      <td>97.818†</td>
      <td>6.14</td>
      <td>6.50</td>
    </tr>
    <tr>
      <td>Arousal</td>
      <td>6.599†</td>
      <td>5.851†</td>
      <td>2.86</td>
      <td>2.75</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Negative<br>Low</b></td>
      <td>Valence</td>
      <td>50.666†</td>
      <td>49.722†</td>
      <td>2.17</td>
      <td>2.75</td>
    </tr>
    <tr>
      <td>Arousal</td>
      <td>30.559†</td>
      <td>30.598†</td>
      <td>4.63</td>
      <td>1.88</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Neutral</b></td> <!-- Merged cell -->
      <td>Valence</td>
      <td>43.063†</td>
      <td>49.541†</td>
      <td>45.176†</td>
      <td>49.675†</td>
    </tr>
    <tr>
      <td>Arousal</td>
      <td>20.506†</td>
      <td>10.674†</td>
      <td>23.793†</td>
      <td>21.311†</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="6">
        <small>
          † GAPED scoring system ranging from 0 to 100 ("very negative"/"insignificantly arousing" to "very positive"/"highly arousing"); 
          the rest follows the NAPS rating scale ranging from 1 to 9 ("very negative"/"relaxed" to "very positive"/"aroused").
        </small>
      </td>
    </tr>
  </tfoot>
</table>

### 3.2. Cognitive
<div style="display: flex; justify-content: space-between; gap: 1px;">
  <div style="width: 33%; text-align: center;">
    <img src="images/cognitive_high.png" alt="Cognitive modulator, mode: high" style="width: 100%; height: auto;">
    <p>High</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="images/cognitive_medium.png" alt="Cognitive modulator, mode: medium" style="width: 100%; height: auto;">
    <p>Medium</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="images/cognitive_low.png" alt="Cognitive modulator, mode: low" style="width: 100%; height: auto;">
    <p>Low</p>
  </div>
</div>

### 3.3. Oddball
<div style="display: flex; justify-content: space-between; gap: 1px;">
  <div style="width: 33%; text-align: center;">
    <img src="images/oddball_noOddball.gif" alt="Oddball modulator, mode: no-oddball" style="width: 100%; height: auto;">
    <p>No-Oddball</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="images/oddball_relevant.gif" alt="Oddball modulator, mode: relevant oddball" style="width: 100%; height: auto;">
    <p>Relevant</p>
  </div>
  <div style="width: 33%; text-align: center;">
    <img src="images/oddball_irrelevant.gif" alt="Oddball modulator, mode: irrelevant oddball" style="width: 100%; height: auto;">
    <p>Irrelevant</p>
  </div>
</div>


### 3.4. Magnitude
<div style="display: flex; justify-content: space-between; gap: 10px;">
  <div style="width: 33%; text-align: center;">
    <audio controls style="width: 100%;">
      <source src="audios/magnitude_highPitch.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <p>High pitch</p>
  </div>

  <div style="width: 33%; text-align: center;">
    <audio controls style="width: 100%;">
      <source src="audios/magnitude_normal.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <p>Normal</p>
  </div>

  <div style="width: 33%; text-align: center;">
    <audio controls style="width: 100%;">
      <source src="audios/magnitude_lowPitch.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <p>Low pitch</p>
  </div>
</div>

### 3.5. Expectation
<div style="display: flex; justify-content: space-between; gap: 5px;">
  <div style="width: 48%; text-align: center;">
    <img src="images/expectation_slowProgressbar.gif" alt="Expectation modulator, mode: slow progressbar" style="width: 100%; height: auto;">
    <p>Slow progressbar</p>
  </div>
  <div style="width: 48%; text-align: center;">
    <img src="images/expectation_fastProgressbar.gif" alt="Expectation modulator, mode: fast progressbar" style="width: 100%; height: auto;">
    <p>Fast progressbar</p>
  </div>
</div>

<div style="margin: 20px 0;">
  <hr>
</div>

## **4. Results**
<div style="width: 100%; text-align: center; margin-bottom: 60px;">
    <img src="images/topography.png" alt="Topographical map of time perception states" style="width: 100%; height: auto;">
    <p>Topographic map of different band powers for time perception states.</p>
</div>

<div style="width: 100%; text-align: center; margin-bottom: 60px;">
    <img src="images/psd.png" alt="PSD plot of time percepsion states" style="width: 100%; height: auto;">
    <p>Spectral activity of EEG channels averaged over all participants, grouped by time perception states.</p>
</div>

<div style="width: 100%; text-align: center; margin-bottom: 60px;">
    <img src="images/SNR-stats.png" alt="Time perception states statistics across 6 frequency bands" style="width: 100%; height: auto;">
    <p>SNR of time perception states in all EEG band powers for each participant.</p>
</div>


## **5. Publication**
-   <a href="https://this-page-intentionally-left-blank.org/" target="_blank" rel="noopener noreferrer">Link to the paper</a>

<div style="margin: 20px 0;">
  <hr>
</div>

<p style="text-align: left;">
  The content of this page is licensed under 
  <a href="https://creativecommons.org/licenses/by-nc/4.0/" target="_blank" rel="noopener noreferrer">
    <img src="https://licensebuttons.net/l/by-nc/4.0/88x31.png" alt="CC BY-NC 4.0 License" style="vertical-align: middle; height: 20px;">
  </a>
</p>





