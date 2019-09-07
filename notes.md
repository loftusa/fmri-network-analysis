## Goal

- Parcellate McKenzie's resting-state fMRI scan into some number of subregions
- Generate covariance matrix that describes the covariance over time for all subregions

### TODOs / beginning tasks / progression

- preprocess with fMRIPrep
- Get covariance of just two voxels over time
- Once done, divide roughly hemispherically, average voxel values, and get covariance of that
- once done, parcellate using atlas and generate parcelwise covariance matrix
