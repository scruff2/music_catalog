# music_catalog
# Open-Source Music Catalog for Audiophiles

Welcome to the Open Source Music Catalog, a community-driven project to compile a comprehensive and detailed catalog of music for audiophiles.

## Project Description

This repository is dedicated to listing songs that this community considers to be of high recording quality, along with their title, artist name(s), album name, genre, release year, key audiophile highlights and lowlights, and other relevant details. Our goal is to create a helpful resource for music enthusiasts, maintained by the community.

## What is Considered "High Recording Quality"?
Although there is a subjective aspect involved,  some songs are so well recorded that even an untrained person will recognize it's beauty when compared to a lesser version.  In the same way, there are some great songs that are obviously very poorly recorded.  You will recognize a great recording and a poor recording when you hear them.  If you don't, then this list is not for you.

## How to Contribute

We welcome contributions from everyone, even if you have no programming experience.

## The Human Readible Format

This catalog uses a very simple, human readible format, as detailed below, and can be easily converted into JSON, Python Dictionaries, etc.

### Adding New Songs

1. **Fork the Repository**: Click on the "Fork" button at the top right of this page to create a copy of this repository under your own GitHub account.
2. **Clone the Repository**: Download the repository to your computer.
   - Go to your forked repository.
   - Click on the "Code" button and select "Download ZIP".
   - Extract the ZIP file on your computer.
3. **Add Your Changes**: Open the extracted folder and find the `catalog.txt` file. Open it in any text editor (like Notepad or TextEdit).
   - Add your new song entry in the format:
     ```
     Title: [Song Title]
     Artist: [Artist Name]
     Album: [Album Name]
     Genre: [Genre]
     Year: [Release Year]
     Audiophile Highlights: [Any interesting positive characteristics that would be of interest to those listening to the song]
     Audiophile Lowlights: [Any interesting negative characteristics that would be of interest to those listening to the song. For example, the problem with that darn tambourine on "Jazz at the Pawnshop" because they recorded it too hot, it is clipping]
     Label: [The record label that released the recording]
     Format: [The format in which the song was released (e.g., Vinyl, CD, Digital)]
     Additional Information: [Any other details]
     ```
4. **Save and Upload Your Changes**:
   - Save the `catalog.txt` file.
   - Go back to your forked repository on GitHub.
   - Click on "Add file" > "Upload files".
   - Drag and drop your updated `catalog.txt` file, and then click on "Commit changes".

5. **Create a Pull Request**: This lets us know you want to add your changes to the main project.
   - Go to the original repository.
   - Click on "Pull Requests" > "New Pull Request".
   - Click on "compare across forks".
   - Select your forked repository and branch.
   - Click on "Create Pull Request" and provide a description of your changes.
   - Click "Create Pull Request" again to submit.

### Updating Information

If you notice any mistakes or outdated information in the catalog, follow the same steps to fork, clone, edit, and submit your changes.

### Suggestions and Discussions

Feel free to use the "Issues" tab on the original repository to suggest new features or discuss improvements. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or need help, feel free to open an issue or contact the repository maintainers.

Thank you for contributing!
