# OpenMined.org

## Getting Started
Make sure you have NPM installed and run `npm install`.  This should get you the required packages in order to compile SASS.

## Contributing
Create an issue first and discuss all changes publicly.  Follow a standard pull request model for version control.

## Compile
To run SASS compilation, run `gulp`.  It will watch all `.scss` files in the root directory for changes and compile them as you save.

## Deploy
To deploy, run `gulp deploy`.  Note that you'll need to have a file in the root directory named `awsaccess.json`.  This is deliberately ignored on Github and **should never be uploaded**.  If you need deployment keys, contact @cereallarceny on the matter.