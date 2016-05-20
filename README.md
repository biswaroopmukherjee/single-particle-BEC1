# Single Particle BEC1

Animate the motion of single particles in the tailored potentials of BEC1! 

![TOF in angled cone](http://i.imgur.com/E6JRtUI.gif "TOF in angled cone")

## Installation

Clone this repo and try the notebooks:

```
git clone https://github.com/biswaroopmukherjee/single-particle-BEC1.git
cd single-particle-BEC1/notebooks
jupyter notebook
```

## Usage

### 2D single-particle simulations

Run `2D shape TOF.ipynb` to simulate the release of particles from a small box inside a larger harmonic potential. Define a box:

```python
box = Box( NumParticles=500 , theta=10 )
```

You can animate it:

```python
box.animate()
```

Or momentum focus it:

```python
box.momentum_focus()
```

Interactions coming soon!

### 3D single-particle simulations

Coming soon.


