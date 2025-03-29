# Weekly/Bi-Weekly Log

## Prompts
Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:

### Date: 
March 28, 2025 


### Number of hours: 
12 hours (5 hours on dataset setup, 4 hours on algorithm exploration, 3 hours on troubleshooting dependencies)

### Rose:
The highlight of this week has been successfully accessing the Waymo dataset and being able to explore its rich multimodal data. I was able to authenticate and download the dataset through Google Cloud, load a TFRecord file, and extract valuable information such as images and LiDAR point clouds. The successful use of TensorFlow and Waymo utilities in Google Colab also felt rewarding, especially after overcoming dependency issues.

### Bud: 
Looking forward, I am excited to start implementing and benchmarking various algorithms for pedestrian behavior prediction, particularly the Warp LSTM, Spatio-temporal Graph Transformer, and AgentFormer. These algorithms align well with the Waymo dataset’s strengths in multi-agent interaction modeling, and I’m eager to analyze their feasibility and performance. I am also intrigued by the idea of exploring pedestrian intent prediction and whether additional annotations or heuristics could be created to address this gap in the dataset. 

### Thorn: 
The main challenge this week was resolving the dependency conflicts during the installation of the Waymo dataset locally, particularly the conflicts with numpy versions. Additionally, working without a GPU has raised concerns about the computational feasibility of running Transformer-based models like Spatio-temporal Graph Transformer and AgentFormer, which require significant processing power. This could limit the scope of experiments if not addressed.

## Additional thought
None

---

