# TileScorer
Implementation of tile scoring method for image patches

Just run the command to get tile score of a image tile=>

python tile_scored.py --tile-path [Path to tile of png or jpeg format]

Please note that tissue percentage is calculated as amount of non-white area in the image in this simple implementation unlike that in IBM processing pipeline where it's calculated by creating tissue mask. The code will be updated with the IBM method of tissue percentage calculator in the next iteration. 
