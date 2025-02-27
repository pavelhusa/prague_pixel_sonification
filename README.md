# Sonification of Prague Data

This repository contains three sound samples of the sonification of data related to Prague's transportation, waste collection, and microclimate. It is a part of the project [Prague Pixels](http://praguepixels.eu), which explores innovative ways to represent urban data through sonification and visualization.

## Technologies Used

- **Ableton Live 11 & Max/MSP**: Used for sound design and prototyping.
- **TypeScript (Max for Live)**: Handles API communication and data processing.
- **Open Sound Control (OSC)**: Synchronizes visualization and sound in real time.

## Sonified Data

### 1. Prague Integrated Transport (PID)

The delays in Prague's metro, tram, and bus networks are represented through sonification:
- Each vehicle is assigned a distinct voice, playing from departure to arrival.
- Different transport types are mapped to unique musical scales for smooth blending.
- Delay affects pitch variation within a 0–100 cent range, causing slight detuning.
- When multiple vehicles experience delays, overlapping voices produce an auditory beating effect, creating a pulsating soundscape.
- Peak-hour delays form a dense, evolving sound environment, while nighttime transport remains steady.

### 2. Waste Collection Sonification

The fill levels of waste bins determine the sound output:
- Each bin produces a chord that changes only when waste is collected.
- The sonification remains mostly static, reflecting the gradual accumulation and removal of waste.

### 3. Prague Microclimate Sonification

Historical and real-time temperature data are converted into sound:
- A baseline triad represents the minimum, average, and maximum temperatures recorded on the same day in the previous year.
- The present-day average temperature is played as a repeating tone.
- Real-time temperature readings from Prague monitoring stations introduce additional notes, creating a melodic pattern that evolves throughout the day.

## Sound Samples

The repository includes three sound samples demonstrating these sonification approaches. Each sample corresponds to one of the datasets described above.

## License

This project is released under the MIT License. Feel free to use it freely, but please ask before making modifications.

## Credits

[Pavel Husa](https://pavel.works) [https://orcid.org/0000-0002-7640-586X](https://orcid.org/0000-0002-7640-586X)

[Cyril Kaplan](https://kps.ff.cuni.cz/cs/ustavkatedra/vyucujici/mgr-cyril-kaplan-ph-d/)[https://orcid.org/0000-0003-2644-5641](https://orcid.org/0000-0003-2644-5641)
