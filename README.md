# release-notes-media

Images for inclusion within product release notes on <www.firefox.com>

## Usage

Any files added or updated within the `media` directory in this repo will be uploaded to the GCP storage bucket for bedrock and be available at the following url: `https://www.firefox.com/media/img/firefox/releasenotes/note-images/<image-file-name>`.

For example: for a file in this repository called `media/114_devtools1.png`, after the sync job runs it will be available at `https://www.firefox.com/media/img/firefox/releasenotes/note-images/114_devtools1.png`.
