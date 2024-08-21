<a href="https://colab.research.google.com/drive/1nFdFwHtcueBdQN17DyuLOevqRybM831D#scrollTo=jiPqid0lceCm" target="_blank">3-Level Password System

## Overview

The Three-Level Password System is a robust security solution that employs multiple layers of authentication to ensure high-level security. This system integrates three distinct authentication methods—text-based, image-based, and behavior-based—to verify user identity, providing a strong defense against unauthorized access. With a simple console interface, it is easy to use and maintain, while also being highly secure against automated attacks.

## Main Features
- Text-Based Authentication: Users must input a secure textual password.
- Image-Based Authentication: Users are required to select images in the correct sequence.
- Behavior-Based Authentication: Users must accurately type a given phrase within a specified time frame.
- Enhanced Security: The system combines different authentication methods to offer maximum protection.
- No Need for External Tools: The system runs entirely within a console, with no requirement for a database or external user interface.

## How It Works
1. Text-Based Authentication: The user inputs their password. If it matches the stored hash, they proceed to the next step.
2. Image-Based Authentication: The user selects images in the correct sequence. If successful, they move to the final step.
3. Behavior-Based Authentication: The user types a specific phrase. Successful completion of all steps grants access.

## Technology Stack
- Python: Manages the authentication logic, including password hashing and timing.
- Hashlib: Ensures secure password hashing.
- Random Module: Shuffles images for the image-based authentication step.
- Time Module: Tracks the typing speed for behavior-based authentication. 

## Installation and Setup
1. **Clone the Repository:**
   ```bash
   git clone <https://colab.research.google.com/drive/1AuY3Pgvz2XWT5tpAJAvqJ-P7KmgdlrDw?usp=sharing](https://colab.research.google.com/drive/1nFdFwHtcueBdQN17DyuLOevqRybM831D#scrollTo=jiPqid0lceCm)>
