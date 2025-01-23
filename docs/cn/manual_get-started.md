# 快速上手
要使用AudioManager播放音频非常简单  

```cs
public class Test : MonoBehaviour
{
    [SerializedField]
    AudioClip clip;
    AudioManager.Play(clip);
}  
```