---
layout: default
title: The CENTRE - Polyphonic Modular Synthesiser
permalink: /product/the-centre/
---

<!-- Hero Section - Image and Description Section -->
<div class="bg-blck text-white py-20 md:py-24">
  <div class="container mx-auto px-6">
    <div class="grid md:grid-cols-2 gap-12 lg:gap-24 items-center">
      <!-- Image Column -->
      <div class="grid aspect-square max-w-lg mx-auto">
        <img src="/assets/img_the_centre_black_angle.png" alt="The CENTRE Black" class="w-full h-full object-contain" style="grid-column: 1; grid-row: 1;">
        <img src="/assets/img_the_centre_silver_angle.png" alt="The CENTRE Silver" class="w-full h-full object-contain" style="grid-column: 1; grid-row: 1; animation: fade-in-out 6s ease-in-out infinite;">
      </div>
      <!-- Text Column -->
      <div class="flex flex-col justify-between h-full py-0">
        <div>
          <h1 class="font-eraz text-5xl md:text-7xl font-bold tracking-tight text-neon-green mt-8">The CENTRE</h1>
          <p class="mt-4 text-xl md:text-2xl text-white/80">A polyphonic, multitimbral, modular-in-modular synthesiser for Eurorack.</p>
        </div>
        <div class="mb-2">
          <div class="flex justify-between items-end mb-4">
            <!-- Left side: Colors -->
            <div>
              <h4 class="text-sm uppercase tracking-widest text-white/70 mb-2">Available colours</h4>
              <div class="flex items-center space-x-4">
                <div class="flex items-center space-x-2">
                  <span class="block w-4 h-4 rounded-full bg-zinc-300 border border-gray-700"></span>
                  <span class="text-sm text-white/90">SILVER</span>
                </div>
                <div class="flex items-center space-x-2">
                  <span class="block w-4 h-4 rounded-full bg-black border border-gray-700"></span>
                  <span class="text-sm text-white/90">BLACK</span>
                </div>
              </div>
            </div>
            <!-- Right side: Prices -->
            <div class="text-right relative">
              <div class="absolute -top-8 right-0 transform -rotate-12">
                <div class="bg-red-600 text-white font-bold uppercase text-xs px-4 py-2 rounded-full shadow-lg shadow-red-500/50">
                  {{ site.data.prices.the_centre.promotion_type }} {{ site.data.prices.the_centre.sale_discount }} OFF
                </div>
              </div>
              <p class="text-xs uppercase tracking-widest text-white/70 pt-4">Current Price</p>
              <p class="text-2xl font-bold text-white">{{ site.data.prices.the_centre.current_price }}</p>
              <p class="text-xs uppercase tracking-widest text-white/70 mt-2">MSRP</p>
              <p class="text-2xl text-white/70 relative inline-block"><span class="block absolute w-full h-0.5 bg-neon-green top-1/2 -translate-y-1/2 -rotate-[10deg]"></span>{{ site.data.prices.the_centre.msrp_price }}</p>
            </div>
          </div>
          <a href="https://shop.1voct.com" target="_blank" class="bg-neon-green text-blck font-bold uppercase tracking-widest px-10 py-5 rounded-full hover:bg-white transition-colors w-full text-center block mt-6">
            Visit the Shop
          </a>
          <p class="text-center text-lg text-white/50 mt-4">Looking for support? <a href="#support" class="text-white/70 hover:text-white underline">Find firmware and user manuals here.</a></p>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bg-blck text-white/80 pb-20 md:pb-24 border-t border-white/10">
    <div class="container mx-auto px-6 prose prose-invert lg:prose-lg prose-headings:font-eraz prose-strong:text-white">
        <h2 class="!text-3xl !mt-0">A New Core for Your Rack</h2>
        <p>The Centre redefines what's possible within a single Eurorack module. At its core, it's a high-fidelity wavetable synthesizer, but its true power lies in its <strong>"modular-in-modular"</strong> architecture.</p>
        <p>This concept allows you to build complex patches by connecting virtual modules—oscillators, filters, envelopes, and LFOs—all within The Centre itself. This approach mirrors the workflow of a DAW while retaining the hands-on immediacy of hardware, supporting up to <strong>4-voice polyphony</strong> to transform an entire patch into a multi-voiced instrument.</p>
    </div>
</div>





<!-- Key Features Section -->
<div class="bg-off-black text-white py-20 md:py-24">
  <div class="container mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-4xl md:text-5xl font-eraz font-bold tracking-tight">Key Features</h2>
    </div>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- Feature Card 1 -->
      <div class="bg-white/5 rounded-2xl p-8">
        <h3 class="font-eraz text-2xl mb-4">Hardware & Connectivity</h3>
        <ul class="space-y-2 text-white/70 list-disc pl-5">
          <li><strong>16 Assignable Knobs</strong> (8 Level, 8 Attenuator)</li>
          <li><strong>4 V/OCT</strong> Calibrated Inputs</li>
          <li><strong>4 CVY</strong> Low-Latency Gate Inputs</li>
          <li><strong>8 CV</strong> General-Purpose Inputs (-10V to +10V)</li>
          <li><strong>4 VOUT</strong> DC-Coupled Outputs (Audio/CV)</li>
          <li>Fast Rotary Encoder for menu navigation</li>
        </ul>
      </div>
      <!-- Feature Card 2 -->
      <div class="bg-white/5 rounded-2xl p-8">
        <h3 class="font-eraz text-2xl mb-4">Core Architecture</h3>
        <ul class="space-y-2 text-white/70 list-disc pl-5">
          <li><strong>Modular-in-Modular</strong> internal patching</li>
          <li><strong>4-Voice Polyphony</strong> across the entire patch</li>
          <li><strong>Virtual Audio Buffers (VBuf)</strong> for internal routing</li>
          <li>Internal CV modulation between all modules</li>
          <li>Full Preset System to save and recall patches</li>
        </ul>
      </div>
      <!-- Feature Card 3 -->
      <div class="bg-white/5 rounded-2xl p-8">
        <h3 class="font-eraz text-2xl mb-4">Featured Modules</h3>
        <ul class="space-y-2 text-white/70 list-disc pl-5">
          <li>Advanced <strong>Wavetable Oscillator</strong> (WTO)</li>
          <li>Flexible 8-Step <strong>Arpeggiator</strong> (ARP)</li>
          <li>AHDSR/AHDR <strong>Envelope Generator</strong> (ENV)</li>
          <li>Custom Shape <strong>LFO</strong> (LFS) with Serum/Vital import</li>
          <li>4-Channel <strong>Gate Divider</strong> (GAT)</li>
          <li>Plus VCF, VCA, Mixers, and more utilities</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<!-- Supported Modules Section -->
<div class="bg-gray-100 text-off-black py-20 md:py-24">
  <div class="container mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-4xl md:text-5xl font-eraz font-bold tracking-tight">Internal Modules</h2>
      <p class="mt-4 text-lg text-gray-600">The "modular-in-modular" design allows you to build patches using a variety of internal virtual modules. Here are the key modules available:</p>
    </div>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- WTO -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Wavetable Oscillator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">WTO</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Advanced wavetable-based sound generator with stereo output and unison capabilities.</p>
        <p class="text-gray-700 text-sm flex-grow">The Wavetable Oscillator (WTO) is the core sound source in The Centre, inspired by software like Serum. It supports loading wavetables from VST formats, allowing up to 16 sub-oscillators per voice in unison mode with detune for thick, chorused sounds. It can handle multiple instances (up to 200 oscillators total across voices) and includes overload protection to manage CPU usage. Controls map to frequency, position, warp, and volume, with CV modulation for dynamic morphing.</p>
      </div>
      <!-- VCO -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Voltage Controlled Oscillator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">VCO</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Classic analog-style oscillator with multiple waveforms.</p>
        <p class="text-gray-700 text-sm flex-grow">The VCO emulates traditional voltage-controlled oscillators, generating sine, square, triangle, sawtooth, and pulse waveforms. It responds to 1V/Oct pitch CV and supports FM/AM modulation. Ideal for subtractive synthesis, it can be synced to clocks for rhythmic effects and used in polyphonic patches.</p>
      </div>
      <!-- LFS -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Low Frequency Shaper</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">LFS</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Shape-based low-frequency modulator with custom editing.</p>
        <p class="text-gray-700 text-sm flex-grow">LFS generates complex modulation shapes beyond standard LFOs, allowing users to load or edit arbitrary waveforms via the integrated Shape Editor. It supports position quantization for rhythmic precision and can be clock-synced. Controls include rate, amplitude, and shape selection, making it versatile for evolving modulations in polyphonic contexts.</p>
      </div>
      <!-- LFO -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Low Frequency Oscillator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">LFO</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Standard low-frequency modulator with various waveforms.</p>
        <p class="text-gray-700 text-sm flex-grow">The LFO provides sine, triangle, square, saw, and random waveforms for modulation. It can be free-running or clock-synced, with controls for rate, depth, and phase. Multiple LFOs can be instantiated per voice for polyphonic modulation of parameters like filter cutoff or pitch.</p>
      </div>
      <!-- ENV -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Envelope Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">ENV</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">AHDSR envelope for shaping amplitude or modulation.</p>
        <p class="text-gray-700 text-sm flex-grow">The ENV is an Attack-Hold-Decay-Sustain-Release generator with multiple types (e.g., linear, exponential) and trigger modes (gate, trigger). It features stages for precise control and can loop for LFO-like behavior. In polyphonic mode, each voice gets its own envelope for independent dynamics.</p>
      </div>
      <!-- VCA -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Voltage Controlled Amplifier</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">VCA</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Amplifier controlled by voltage for volume shaping.</p>
        <p class="text-gray-700 text-sm flex-grow">The VCA modulates audio or CV signals with an envelope or LFO input. It supports sidechain compression for ducking effects and operates in linear or exponential modes. Essential for polyphonic patches, it ensures per-voice amplitude control.</p>
      </div>
      <!-- BRM -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Balanced Ring Modulator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">BRM</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Ring modulation effect for metallic tones.</p>
        <p class="text-gray-700 text-sm flex-grow">BRM multiplies two signals to create sum/difference frequencies, producing bell-like or robotic sounds. It's balanced to minimize carrier bleed and supports CV control over modulation depth. Useful in wavetable patches for adding harmonics.</p>
      </div>
      <!-- SMP -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Sample Player</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">SMP</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Plays back samples with looping and grain options.</p>
        <p class="text-gray-700 text-sm flex-grow">SMP loads samples from SD card, supporting looping, granular playback, and pitch/speed control via CV. It can trigger grains for textural effects and works in polyphonic mode for layered samples or drum hits.</p>
      </div>
      <!-- NOI -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Noise Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">NOI</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Produces various noise types for percussion or texture.</p>
        <p class="text-gray-700 text-sm flex-grow">NOI generates white, pink, brown, and other noise waveforms, filterable for specific spectra. It's useful for snares, hats, or modulation sources in synthesis patches.</p>
      </div>
      <!-- DLY -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Delay</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">DLY</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">LoFi delay effect with feedback.</p>
        <p class="text-gray-700 text-sm flex-grow">The DLY is a low-fidelity delay with time, feedback, and mix controls, syncable to clock for rhythmic echoes. It adds space and movement to sounds, with CV modulation for dub-style effects.</p>
      </div>
      <!-- DST -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Distortion</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">DST</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Overdrive and distortion for adding grit.</p>
        <p class="text-gray-700 text-sm flex-grow">DST applies waveshaping distortion, from subtle warmth to aggressive clipping. Controls include drive, tone, and mix, making it ideal for fattening wavetables or VCOs.</p>
      </div>
      <!-- VCF -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Voltage Controlled Filter</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">VCF</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Multi-mode filter with resonance.</p>
        <p class="text-gray-700 text-sm flex-grow">The VCF offers low-pass, high-pass, band-pass, and notch modes, with ladder, bi-quad, and comb types. It tracks 1V/Oct for key-following and supports resonance up to self-oscillation for classic synth sounds.</p>
      </div>
      <!-- DRC -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Drum Rack</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">DRC</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Sample-based drum machine with MIDI triggering.</p>
        <p class="text-gray-700 text-sm flex-grow">DRC loads drum samples into racks, triggerable via MIDI or gates for polyphonic percussion. It supports velocity sensitivity and mixing, enabling multi-timbral drum layers alongside melodic voices.</p>
      </div>
      <!-- CLK -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Clock Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">CLK</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Generates clocks for synchronization.</p>
        <p class="text-gray-700 text-sm flex-grow">CLK produces internal clocks based on BPM, with divisions and external sync options. It outputs pulses (1-24 PPQN) to drive sequencers, LFOs, or other modules for tempo-locked performance.</p>
      </div>
      <!-- GAT -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Gate Divider</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">GAT</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Divides incoming gates for rhythmic patterns.</p>
        <p class="text-gray-700 text-sm flex-grow">GAT takes clock/gate inputs and divides them (e.g., /2, /3) to create sub-rhythms. It's essential for polyrhythmic setups and can reset via CV.</p>
      </div>
      <!-- EUC -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Euclidean Rhythm Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">EUC</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Generates Euclidean patterns for complex rhythms.</p>
        <p class="text-gray-700 text-sm flex-grow">EUC creates evenly distributed pulses within steps, with controls for hits, length, and rotation. CV-modulable for evolving beats, it's great for generative music.</p>
      </div>
      <!-- PLY -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Polyrhythm</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">PLY</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Creates overlapping rhythmic layers.</p>
        <p class="text-gray-700 text-sm flex-grow">PLY generates multiple independent rhythms that overlay for polyrhythmic complexity. Controls include individual rates and gates, syncable to master clock.</p>
      </div>
      <!-- RNG -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Random Note Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">RNG</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Produces random pitches within constraints.</p>
        <p class="text-gray-700 text-sm flex-grow">RNG outputs random notes or CV values, quantized to scales. It can be clock-triggered for melodic randomness in arps or sequences.</p>
      </div>
      <!-- QNT -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Quantiser</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">QNT</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Snaps CV to musical scales.</p>
        <p class="text-gray-700 text-sm flex-grow">QNT quantizes incoming CV to predefined or custom scales (including Scala format). It has simple and advanced modes for musical or microtonal tuning.</p>
      </div>
      <!-- ARP -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Arpeggiator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">ARP</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Breaks chords into sequenced notes.</p>
        <p class="text-gray-700 text-sm flex-grow">ARP sequences held notes in patterns (up, down, random) with octave range, rests, and duration control. It can be externally positioned via CV for integration with sequencers.</p>
      </div>
      <!-- CHD -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Chords Generator</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">CHD</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Generates polyphonic chords from single notes.</p>
        <p class="text-gray-700 text-sm flex-grow">CHD turns single-note inputs into chords (e.g., major, minor) with voicing options. It supports duration and inversion, ideal for polyphonic harmony in limited-voice setups.</p>
      </div>
      <!-- MID -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>MIDI</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">MID</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Handles MIDI input/output for control.</p>
        <p class="text-gray-700 text-sm flex-grow">MID module processes MIDI notes, CCs, and clocks in single-note, polyphonic, or drum modes. It enables external control and multi-timbral routing via channels.</p>
      </div>
      <!-- MIX -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Mixer</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">MIX</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Mixes multiple signals with levels.</p>
        <p class="text-gray-700 text-sm flex-grow">MIX combines audio/CV sources with per-channel levels and panning. It supports polyphonic downmixing for routing multiple voices to fewer outputs.</p>
      </div>
      <!-- OUT -->
      <div class="bg-white rounded-2xl p-8 flex flex-col">
        <h3 class="font-eraz text-2xl mb-2 flex items-center justify-between"><span>Output</span><code class="text-sm font-mono bg-gray-200 text-gray-800 rounded px-2 py-1">OUT</code></h3>
        <p class="text-gray-600 italic mb-4 text-sm">Final audio output stage.</p>
        <p class="text-gray-700 text-sm flex-grow">OUT handles the module's physical and virtual outputs, with gain staging and monitoring. It ensures clean signal routing in multi-timbral setups.</p>
      </div>
    </div>
  </div>
</div>


<!-- Support Section -->
<div id="support" class="bg-off-black text-white py-20 md:py-24 scroll-mt-20">
  <div class="container mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-4xl md:text-5xl font-eraz font-bold tracking-tight">Support & Downloads</h2>
    </div>
    <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
      <!-- Column 1: Firmware -->
      <div>
        <h3 class="font-eraz text-2xl mb-4">Firmware</h3>
        <div class="space-y-3">
          {% if site.data.products.the_centre.stable_firmware != "" %}
          <a href="{{ site.data.products.the_centre.stable_firmware }}" class="flex items-center space-x-3 bg-white/10 p-4 rounded-lg shadow-sm hover:shadow-md transition-shadow">
            <span class="text-lg">⬇️</span>
            <span class="font-bold">Download Stable Firmware</span>
          </a>
          {% endif %}
          {% if site.data.products.the_centre.beta_firmware != "" %}
          <a href="{{ site.data.products.the_centre.beta_firmware }}" class="flex items-center space-x-3 bg-white p-4 rounded-lg shadow-sm hover:shadow-md transition-shadow">
            <span class="text-lg">🧪</span>
            <span class="font-bold">Download BETA Firmware</span>
          </a>
          {% endif %}
        </div>
      </div>
      <!-- Column 2: User Manuals -->
      <div>
        <h3 class="font-eraz text-2xl mb-4">User Manuals</h3>
        <div class="space-y-3">
          {% for manual in site.data.products.the_centre.user_manuals %}
          <a href="{{ manual.user_manual_url }}" class="flex items-center space-x-3 bg-white/10 hover:bg-white/20 p-4 rounded-lg transition-colors">
            <img src="https://flagcdn.com/w40/{{ manual.country_code }}.png" alt="{{ manual.country_code | upcase }} flag" class="w-6 h-auto">
            <span class="font-bold">Download Manual ({{ manual.country_code | upcase }})</span>
          </a>
          {% endfor %}
        </div>
      </div>
    </div>
  </div>
</div>
