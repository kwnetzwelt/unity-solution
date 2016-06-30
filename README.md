# unity-solution
Auto generates a travis compatible Unity3d C# solution. This is compatible with Unity 5.4. 

## Installation
    npm install -g unity-solution-2

## Usage
    unitysolution ./UnityScriptsFolderName [TargetPlatform]
    
The second parameter is optional and can be one of the following:
* Standalone
* iOS
* Android
* WebGL

## Example
    unitysolution ./UnityGameBase iOS
    xbuild /p:Configuration=Debug unity.sln
    
Live example for a travis configuration can be found at the [ugb-source travis config](https://github.com/kwnetzwelt/ugb-source/blob/development/.travis.yml)
