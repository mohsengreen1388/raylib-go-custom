#rmodels.c
// Get framePoses for per bone
Transform GetBonePose(ModelAnimation anim,int frameCount,int boneId)
// Get bindPose
Transform GetBindPose(Model model,int boneId)
// Get NameBone
char* GetBoneName(Model model,int boneId)
// Get ParentBone
int GetParentBone(Model model,int boneId)
// Get BoneCount
int BoneCount(Model model)

#raylib.h
RLAPI Transform GetBonePose(ModelAnimation anim,int frameCount,int boneId);             // Get framePoses for per bone
RLAPI Transform GetBindPose(Model model,int boneId);                                    // Get bindPose
RLAPI char* GetBoneName(Model model,int boneId);                                        // Get NameBone
RLAPI int GetParentBone(Model model,int boneId);                                       // Get ParentBone
RLAPI int BoneCount(Model model);                                                      //BoneCount

#rmodels.go
// Get framePoses for per bone
func GetBonePose(anim ModelAnimation, frame int32,boneId int32)Transform
// Get bindPose Model
func GetBindPose(model Model,boneId int32)Transform
// Get framePoses for per bone
func BoneCount(model Model)int32
//Get NameBone
func GetBoneName(model Model,boneId int)string
// Get ParentBone
func GetParentBone(model Model,boneId int)int32