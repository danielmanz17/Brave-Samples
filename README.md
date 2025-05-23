<!-- Rendering the spectrograms, alongside a description and the audio file -->

A selection of spectrogram & audio samples, produced by applying transformations to neural network architecture, using the 
Brave synthesiser. Here, I present a spectrogram/raw audio file of the samples, along with a description of the transformations
that have been applied.

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>The darbouka RAVE model without any transformations applied to the underlying network. This should act as a baseline when inspecting the other samples.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample1.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>Applying &Delta;y = 0.47 to encoder.net.1.bias.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample1.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample2.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>Applying &Delta;y = 0.3 at encoder.net.2.bias.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample2.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample3.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>Applying a scale factor of -0.79 to encoder.net.7.weight.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample3.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample4.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>Applying &Delta;y = -0.5 at encoder.net.10.weight.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample4.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 40px;">
  <img src="spectrograms/sample5.png" alt="Example" style="width: 650px; margin-right: 20px;">
  <div style="display: flex; flex-direction: column; justify-content: center;">
    <div>
      <p>Applying &Delta;x = 0.195 at encoder.net.14.weight.</p>
    </div>
    <audio controls style="width: 350px; margin-top: 10px;">
      <source src="audio/sample5.wav" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</div>