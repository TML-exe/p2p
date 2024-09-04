# p2p
a p2p network allowing multi peer communication, made to allow encrypted and secure file sharing and backup.
# P2P Secure File Sharing System

## Overview

This project is a Peer-to-Peer (P2P) secure file-sharing system that allows users to securely distribute and retrieve files across multiple peers. The system is designed with encryption to protect the confidentiality of the data during transfer. Additionally, files are split into chunks and distributed across multiple peers to enhance security and redundancy.

## Features

- **P2P Communication**: Connects multiple peers for file sharing.
- **File Encryption**: Uses AES encryption to secure files during transmission.
- **File Splitting**: Files are split into smaller chunks, each stored separately across different peers.
- **File Reconstruction**: Chunks are reassembled to retrieve the original file when requested.
- **GUI Interface**: Simple graphical user interface (GUI) built with Pygame for sending and requesting files.
- **Self Entry Mode**: Allows users to distribute files within their own computer’s memory for added security.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the server**:
    ```bash
    python server.py
    ```

4. **Run the client**:
    ```bash
    python client.py
    ```

5. **Run the GUI**:
    ```bash
    python main.py
    ```

## Usage

### Sending Files

1. Launch the application.
2. Choose the **Send File** option in the GUI.
3. Enter the file path and click **Send**.

### Requesting Files

1. Choose the **Request File** option in the GUI.
2. Enter the file name and click **Request**.
3. The file will be reconstructed from the chunks and saved to the specified location.

### Self Entry Mode

1. Choose the **Self Entry** option in the GUI.
2. Enter the file path and click **Send**.
3. The file will be distributed within your own system's memory.

## License

This project is licensed under the **GNU General Public License v3.0**. 

You may use, modify, and distribute this software under the terms of the GPL-3.0 license. For more details, see the [LICENSE](LICENSE) file.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## Acknowledgments

- The encryption system utilizes the [PyCryptodome](https://pycryptodome.readthedocs.io/en/latest/) library for AES encryption.
- The GUI is built using [Pygame](https://www.pygame.org/news).

## Contact

For any questions or feedback, please contact landistalia@gmail.com or open an issue on the repository.


