# digital-art
class DigitalArtwork:
    def __init__(self, title, artist, medium, dimensions):
        self.title = title
        self.artist = artist
        self.medium = medium
        self.dimensions = dimensions

    def display_info(self):
        print("Digital Artwork Information:")
        print(f"Title: {self.title}")
        print(f"Artist: {self.artist}")
        print(f"Medium: {self.medium}")
        print(f"Dimensions: {self.dimensions}")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the DigitalArtwork class
    my_artwork = DigitalArtwork(
        title="Abstract Composition",
        artist="John Doe",
        medium="Digital Painting",
        dimensions="1920x1080 pixels"
    )

    # Displaying information about the digital artwork
    my_artwork.display_info()
