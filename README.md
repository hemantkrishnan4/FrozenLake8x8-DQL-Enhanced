# FrozenLake8x8-DQL-Enhanced

Q-Learning - Frozen Lake 8x8 Enhanced

Welcome to the FrozenLake8x8-DQL-Enhanced repository! This project is designed to provide an enhanced learning experience for understanding Q-Learning in the FrozenLake-v1 environment. The enhancements include visualizing Q values in real-time, enlarging the map for better readability, and incorporating shortcut keys for animation control.

## Features

1\. **Real-time Q Value Visualization**: The Q values are dynamically overlaid on each cell of the map. This allows you to witness the Q values update in real-time as the agent undergoes training, providing valuable insights into the learning process.

2\. **Enlarged Map Display**: The map is enlarged to fill the entire screen, ensuring that the overlaid Q values are easier to read. This enhancement improves the overall visibility and clarity of the learning environment.

3\. **Shortcut Keys for Animation Control**: To facilitate a smoother learning experience, shortcut keys have been implemented to control the animation speed. You can speed up or slow down the training animation based on your preference.

## Test Output NO Slipping
![frozen_enhanced](https://github.com/hemantkrishnan4/FrozenLake8x8-DQL-Enhanced/assets/96692095/38d22b95-a4b5-44d8-b7aa-3f348a7bd142)

## Training Graph
![frozen_lake8x8](https://github.com/hemantkrishnan4/FrozenLake8x8-DQL-Enhanced/assets/96692095/a750fab8-1429-4ca1-bbbf-4d6eeb08f540)



## Code Reference

1\. **frozen_lake_qe.py**: This file is nearly identical to the original `frozen_lake_q.py`, with the key difference being the utilization of the `frozen_lake_enhanced.py` environment. Use this script to execute Q-Learning in the enhanced FrozenLake-v1 environment.

2\. **frozen_lake_enhanced.py**: This module provides the FrozenLake-v1 environment overlaid with Q values. You don't need an in-depth understanding of this code; it serves as the foundation for visual enhancements.

## Getting Started

Follow these steps to get started with the FrozenLake8x8-DQL-Enhanced project:

1\. Clone the repository to your local machine.

```bash

git clone https://github.com/your-username/FrozenLake8x8-DQL-Enhanced.git

cd FrozenLake8x8-DQL-Enhanced

```

2\. Run the Q-Learning algorithm using the enhanced environment.

```bash

python frozen_lake_qe.py

```

3\. Explore and modify the code as needed, and enjoy the visualized Q-Learning experience!

## Acknowledgement

This project builds upon the work from [JohnnyCode8's Gym Solutions](https://github.com/johnnycode8/gym_solutions?tab=readme-ov-file#q-learning---frozen-lake-8x8-enhanced). We would like to express our gratitude for their contributions and inspiration to enhance the Frozen Lake 8x8 environment for Q-Learning.

## License

This project is licensed under the [MIT License](LICENSE.md) - see the [LICENSE.md](LICENSE.md) file for details.

Feel free to contribute, provide feedback, or report issues. Happy learning with Q-Learning in the enhanced Frozen Lake 8x8 environment!
