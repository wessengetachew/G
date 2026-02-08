# G

https://wessengetachew.github.io/G/

Farey Sequence Summatory Function Research Platform

A comprehensive web-based mathematical research tool for exploring and visualizing Farey sequences, number theory relationships, and harmonic analysis through interactive visualizations and audio synthesis.

OVERVIEW

This platform provides an integrated environment for investigating the mathematical properties of Farey sequences, their summatory functions, and related number-theoretic constructs. The application combines real-time computational analysis with multi-modal visualization techniques and harmonic audio synthesis to facilitate exploration of patterns in rational number distributions.

FEATURES

Mathematical Analysis

+ Farey sequence generation and summatory function computation up to arbitrary denominators
+ Real-time calculation of Euler's totient function, Möbius function, and prime factorizations
+ Divisor sum analysis and asymptotic approximation comparisons
+ Riemann hypothesis horizon tracking and error analysis
+ Modular arithmetic visualization with custom labeling systems

Visualization Tools

+ Interactive charts with zoom and pan capabilities powered by Chart.js
+ Ford circle rendering with dynamic spacing and scaling
+ Maxwell field theory analogies with multiple colorization schemes (Viridis, Plasma, Inferno, CoolWarm, Electric)
+ Vector field displays with density, flow, and Poynting vector modes
+ Wave propagation animations
+ Streamline visualizations
+ Phase space diagrams

Harmonic Audio Synthesis

+ Just intonation frequency mapping from rational number ratios
+ Real-time audio oscillator with multiple waveforms (sine, square, sawtooth, triangle)
+ ADSR envelope controls (Attack, Decay, Sustain, Release)
+ Harmonic interval playback with customizable tempo
+ Audio visualization with waveform and frequency spectrum displays
+ Support for multiple tuning systems and musical scales
+ Phase modulation controls

Interactive Features

+ Customizable computation ranges and precision settings
+ Export capabilities for chart images and numerical data (CSV format)
+ Responsive controls for parameter adjustment
+ Real-time updates across all visualization modes
+ Collapsible panel system for organized workspace management

TECHNICAL SPECIFICATIONS

Dependencies

The platform utilizes the following external libraries via CDN:

+ Chart.js 3.9.1 (charting and visualization)
+ Hammer.js 2.0.8 (touch gesture support)
+ chartjs-plugin-zoom 2.0.1 (chart interaction)
+ html2canvas 1.4.1 (screenshot export functionality)

Core Technologies

+ Pure JavaScript (ES6+) for all computational logic
+ HTML5 Canvas API for custom visualizations
+ Web Audio API for sound synthesis
+ CSS Grid and Flexbox for responsive layouts
+ No build process or compilation required

USAGE

Getting Started

1. Clone or download this repository
2. Open index.html in a modern web browser (Chrome, Firefox, Safari, or Edge recommended)
3. No server or installation required; all functionality runs client-side

Basic Operation

The interface is organized into expandable sections accessible from the sidebar:

+ Core Analysis: View summatory function values, asymptotic approximations, and error metrics
+ Horizon Tracking: Monitor fractions approaching the Riemann hypothesis horizon
+ Advanced Analysis: Access detailed statistical breakdowns and distribution analyses
+ Visualizations: Generate Ford circles, field theory analogs, and phase diagrams
+ Harmonic Audio: Explore the musical relationships encoded in Farey fractions
+ Modular Labels: Create custom labeling systems for modular arithmetic visualization

Parameter Configuration

Key parameters can be adjusted through the control panels:

+ N (Maximum Denominator): Controls the range of Farey sequence computation (2 to 10000)
+ Precision: Number of decimal places for display purposes
+ Visualization Settings: Grid display, prime highlighting, vector overlays
+ Audio Settings: Waveform type, ADSR envelope, tempo, and tuning system

Exporting Results

Charts and data can be exported via dedicated buttons:

+ Save Chart as Image: Generates PNG downloads of current visualizations
+ Export Data: Creates CSV files containing computed values for external analysis

MATHEMATICAL BACKGROUND

Farey Sequences

The Farey sequence F(n) is the ascending sequence of completely reduced fractions between 0 and 1 having denominators less than or equal to n. This platform computes the summatory function, which represents the cumulative sum of these fractions, and analyzes its relationship to theoretical predictions based on the Riemann hypothesis.

Number Theoretic Functions

+ Euler's Totient Function φ(n): Counts integers up to n that are coprime to n
+ Möbius Function μ(n): Arithmetic function based on prime factorization
+ Divisor Functions σ_k(n): Sum of kth powers of divisors

Harmonic Relationships

The platform maps Farey fractions to musical frequencies using just intonation principles, where rational number ratios correspond to harmonic intervals. This provides an auditory dimension to the exploration of number-theoretic patterns.

BROWSER COMPATIBILITY

This application is optimized for modern browsers with full ES6+ JavaScript support, Canvas API, and Web Audio API capabilities:

+ Chrome/Edge 90 or later
+ Firefox 88 or later
+ Safari 14 or later

Mobile browsers are supported with touch-optimized controls, though desktop experience is recommended for detailed analysis work.

PERFORMANCE NOTES

Computation complexity scales with the chosen value of N. For optimal performance:

+ N values up to 1000: Instantaneous computation
+ N values 1000 to 5000: Processing time under 2 seconds
+ N values above 5000: May experience delays depending on device capabilities

Large N values combined with dense visualizations may impact rendering performance on lower-end devices. Consider reducing visualization density or disabling certain overlays if experiencing lag.

LICENSE

This project is provided as-is for educational and research purposes. Users are free to modify and extend the codebase for their own mathematical investigations.

CONTRIBUTING

Contributions, bug reports, and feature suggestions are welcome. Areas of particular interest for expansion include:

+ Additional number-theoretic function visualizations
+ Alternative colorization schemes for field representations
+ Extended harmonic synthesis modes
+ Performance optimizations for large N computations
+ Mobile interface refinements

ACKNOWLEDGMENTS

This platform synthesizes concepts from analytic number theory, harmonic analysis, and electromagnetic field theory to create a unique multi-sensory exploration environment for Farey sequences and related mathematical structures.

CONTACT

For questions, collaboration opportunities, or technical support, please open an issue in the repository or contact the maintainer directly.





