# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 7 | **Total Symbols Extracted:** 419 | **Total Imports:** 127

## Structural Knowledge Map
```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    neurologos_tricameral_loss5_4_py["neurologos_tricameral_loss5.4.py (py)"]
    class neurologos_tricameral_loss5_4_py mod;
    neurologos_tricameral_loss5_4_py_preprocess_and_cache_spectrograms["preprocess_and_cache_spectrograms"]
    class neurologos_tricameral_loss5_4_py_preprocess_and_cache_spectrograms fn;
    neurologos_tricameral_loss5_4_py --> neurologos_tricameral_loss5_4_py_preprocess_and_cache_spectrograms
    neurologos_tricameral_loss5_4_py_apply_emergency_fixes["apply_emergency_fixes"]
    class neurologos_tricameral_loss5_4_py_apply_emergency_fixes fn;
    neurologos_tricameral_loss5_4_py --> neurologos_tricameral_loss5_4_py_apply_emergency_fixes
    neurologos_tricameral_loss5_4_py_setup_flickr8k_with_audio["setup_flickr8k_with_audio"]
    class neurologos_tricameral_loss5_4_py_setup_flickr8k_with_audio fn;
    neurologos_tricameral_loss5_4_py --> neurologos_tricameral_loss5_4_py_setup_flickr8k_with_audio
    neurologos_tricameral_loss5_4_py_build_vocab_flickr["build_vocab_flickr"]
    class neurologos_tricameral_loss5_4_py_build_vocab_flickr fn;
    neurologos_tricameral_loss5_4_py --> neurologos_tricameral_loss5_4_py_build_vocab_flickr
    neurologos_tricameral_loss5_4_py_HierarchicalEpisodicMemory["HierarchicalEpisodicMemory"]
    class neurologos_tricameral_loss5_4_py_HierarchicalEpisodicMemory cls;
    neurologos_tricameral_loss5_4_py --> neurologos_tricameral_loss5_4_py_HierarchicalEpisodicMemory
    neurologos_tricameral_loss8_0_py["neurologos_tricameral_loss8.0.py (py)"]
    class neurologos_tricameral_loss8_0_py mod;
    neurologos_tricameral_loss8_0_py_preprocess_and_cache_spectrograms["preprocess_and_cache_spectrograms"]
    class neurologos_tricameral_loss8_0_py_preprocess_and_cache_spectrograms fn;
    neurologos_tricameral_loss8_0_py --> neurologos_tricameral_loss8_0_py_preprocess_and_cache_spectrograms
    neurologos_tricameral_loss8_0_py_apply_emergency_fixes["apply_emergency_fixes"]
    class neurologos_tricameral_loss8_0_py_apply_emergency_fixes fn;
    neurologos_tricameral_loss8_0_py --> neurologos_tricameral_loss8_0_py_apply_emergency_fixes
    neurologos_tricameral_loss8_0_py_setup_flickr8k_with_audio["setup_flickr8k_with_audio"]
    class neurologos_tricameral_loss8_0_py_setup_flickr8k_with_audio fn;
    neurologos_tricameral_loss8_0_py --> neurologos_tricameral_loss8_0_py_setup_flickr8k_with_audio
    neurologos_tricameral_loss8_0_py_build_vocab_flickr["build_vocab_flickr"]
    class neurologos_tricameral_loss8_0_py_build_vocab_flickr fn;
    neurologos_tricameral_loss8_0_py --> neurologos_tricameral_loss8_0_py_build_vocab_flickr
    neurologos_tricameral_loss8_0_py_HierarchicalEpisodicMemory["HierarchicalEpisodicMemory"]
    class neurologos_tricameral_loss8_0_py_HierarchicalEpisodicMemory cls;
    neurologos_tricameral_loss8_0_py --> neurologos_tricameral_loss8_0_py_HierarchicalEpisodicMemory
    neurologos_tricameral_loss2_7_py["neurologos_tricameral_loss2.7.py (py)"]
    class neurologos_tricameral_loss2_7_py mod;
    neurologos_tricameral_loss2_7_py_setup_flickr8k_with_audio["setup_flickr8k_with_audio"]
    class neurologos_tricameral_loss2_7_py_setup_flickr8k_with_audio fn;
    neurologos_tricameral_loss2_7_py --> neurologos_tricameral_loss2_7_py_setup_flickr8k_with_audio
    neurologos_tricameral_loss2_7_py_build_vocab_flickr["build_vocab_flickr"]
    class neurologos_tricameral_loss2_7_py_build_vocab_flickr fn;
    neurologos_tricameral_loss2_7_py --> neurologos_tricameral_loss2_7_py_build_vocab_flickr
    neurologos_tricameral_loss2_7_py_HierarchicalEpisodicMemory["HierarchicalEpisodicMemory"]
    class neurologos_tricameral_loss2_7_py_HierarchicalEpisodicMemory cls;
    neurologos_tricameral_loss2_7_py --> neurologos_tricameral_loss2_7_py_HierarchicalEpisodicMemory
    neurologos_tricameral_loss2_7_py_NeurocognitiveSystem["NeurocognitiveSystem"]
    class neurologos_tricameral_loss2_7_py_NeurocognitiveSystem cls;
    neurologos_tricameral_loss2_7_py --> neurologos_tricameral_loss2_7_py_NeurocognitiveSystem
    neurologos_tricameral_loss2_7_py_LanguageMetrics["LanguageMetrics"]
    class neurologos_tricameral_loss2_7_py_LanguageMetrics cls;
    neurologos_tricameral_loss2_7_py --> neurologos_tricameral_loss2_7_py_LanguageMetrics
    neurologos_tricameral_loss3_9_py["neurologos_tricameral_loss3.9.py (py)"]
    class neurologos_tricameral_loss3_9_py mod;
    neurologos_tricameral_loss3_9_py_compute_loss["compute_loss"]
    class neurologos_tricameral_loss3_9_py_compute_loss fn;
    neurologos_tricameral_loss3_9_py --> neurologos_tricameral_loss3_9_py_compute_loss
    neurologos_tricameral_loss3_9_py_NeurocognitiveSystem["NeurocognitiveSystem"]
    class neurologos_tricameral_loss3_9_py_NeurocognitiveSystem cls;
    neurologos_tricameral_loss3_9_py --> neurologos_tricameral_loss3_9_py_NeurocognitiveSystem
    neurologos_tricameral_loss3_9_py_LinguisticFeedbackLoop["LinguisticFeedbackLoop"]
    class neurologos_tricameral_loss3_9_py_LinguisticFeedbackLoop cls;
    neurologos_tricameral_loss3_9_py --> neurologos_tricameral_loss3_9_py_LinguisticFeedbackLoop
    neurologos_tricameral_loss3_9_py_LanguageMetrics["LanguageMetrics"]
    class neurologos_tricameral_loss3_9_py_LanguageMetrics cls;
    neurologos_tricameral_loss3_9_py --> neurologos_tricameral_loss3_9_py_LanguageMetrics
    neurologos_tricameral_loss3_9_py_TriangulatedMedicalSystem["TriangulatedMedicalSystem"]
    class neurologos_tricameral_loss3_9_py_TriangulatedMedicalSystem cls;
    neurologos_tricameral_loss3_9_py --> neurologos_tricameral_loss3_9_py_TriangulatedMedicalSystem
    neurologos_tricameral_loss4_5_py["neurologos_tricameral_loss4.5.py (py)"]
    class neurologos_tricameral_loss4_5_py mod;
    neurologos_tricameral_loss4_5_py_compute_loss["compute_loss"]
    class neurologos_tricameral_loss4_5_py_compute_loss fn;
    neurologos_tricameral_loss4_5_py --> neurologos_tricameral_loss4_5_py_compute_loss
    neurologos_tricameral_loss4_5_py_LanguageMetrics["LanguageMetrics"]
    class neurologos_tricameral_loss4_5_py_LanguageMetrics cls;
    neurologos_tricameral_loss4_5_py --> neurologos_tricameral_loss4_5_py_LanguageMetrics
    neurologos_tricameral_loss4_5_py_TriangulatedMedicalSystem["TriangulatedMedicalSystem"]
    class neurologos_tricameral_loss4_5_py_TriangulatedMedicalSystem cls;
    neurologos_tricameral_loss4_5_py --> neurologos_tricameral_loss4_5_py_TriangulatedMedicalSystem
    neurologos_tricameral_loss4_5_py_StableLiquidNeuron["StableLiquidNeuron"]
    class neurologos_tricameral_loss4_5_py_StableLiquidNeuron cls;
    neurologos_tricameral_loss4_5_py --> neurologos_tricameral_loss4_5_py_StableLiquidNeuron
    neurologos_tricameral_loss4_5_py_RightHemisphere["RightHemisphere"]
    class neurologos_tricameral_loss4_5_py_RightHemisphere cls;
    neurologos_tricameral_loss4_5_py --> neurologos_tricameral_loss4_5_py_RightHemisphere
    app_py["app.py (py)"]
    class app_py mod;
    install_sh["install.sh (sh)"]
    class install_sh mod;
    ext_os["os"]
    class ext_os ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_os
    ext_pathlib["pathlib"]
    class ext_pathlib ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_pathlib
    ext_collections["collections"]
    class ext_collections ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_collections
    ext_torch["torch"]
    class ext_torch ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torch
    ext_torch_nn["torch.nn"]
    class ext_torch_nn ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torch_nn
    ext_torch_nn_functional["torch.nn.functional"]
    class ext_torch_nn_functional ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torch_nn_functional
    ext_torchvision_models["torchvision.models"]
    class ext_torchvision_models ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torchvision_models
    ext_torchvision["torchvision"]
    class ext_torchvision ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torchvision
    ext_torchaudio["torchaudio"]
    class ext_torchaudio ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torchaudio
    ext_torchaudio_transforms["torchaudio.transforms"]
    class ext_torchaudio_transforms ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torchaudio_transforms
    ext_torch_utils_data["torch.utils.data"]
    class ext_torch_utils_data ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torch_utils_data
    ext_PIL["PIL"]
    class ext_PIL ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_PIL
    ext_numpy["numpy"]
    class ext_numpy ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_numpy
    ext_tqdm["tqdm"]
    class ext_tqdm ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_tqdm
    ext_warnings["warnings"]
    class ext_warnings ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_warnings
    ext_kagglehub["kagglehub"]
    class ext_kagglehub ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_kagglehub
    ext_subprocess["subprocess"]
    class ext_subprocess ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_subprocess
    ext_urllib_request["urllib.request"]
    class ext_urllib_request ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_urllib_request
    ext_zipfile["zipfile"]
    class ext_zipfile ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_zipfile
    ext_shutil["shutil"]
    class ext_shutil ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_shutil
    ext_soundfile["soundfile"]
    class ext_soundfile ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_soundfile
    ext_time["time"]
    class ext_time ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_time
    ext_functools["functools"]
    class ext_functools ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_functools
    neurologos_tricameral_loss2_7_py -.->|imports| ext_collections
    neurologos_tricameral_loss2_7_py -.->|imports| ext_torch_utils_data
    ext_google_colab["google.colab"]
    class ext_google_colab ext;
    neurologos_tricameral_loss2_7_py -.->|imports| ext_google_colab
    neurologos_tricameral_loss2_7_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss2_7_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss2_7_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss2_7_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torch
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torch_nn
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss3_9_py -.->|imports| ext_numpy
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torchvision
    neurologos_tricameral_loss3_9_py -.->|imports| ext_PIL
    neurologos_tricameral_loss3_9_py -.->|imports| ext_os
    neurologos_tricameral_loss3_9_py -.->|imports| ext_collections
    neurologos_tricameral_loss3_9_py -.->|imports| ext_torchvision_models
    neurologos_tricameral_loss3_9_py -.->|imports| ext_tqdm
    neurologos_tricameral_loss3_9_py -.->|imports| ext_warnings
    neurologos_tricameral_loss3_9_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss3_9_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss3_9_py -.->|imports| ext_shutil
    neurologos_tricameral_loss3_9_py -.->|imports| ext_google_colab
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torch
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torch_nn
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss4_5_py -.->|imports| ext_numpy
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torchvision
    neurologos_tricameral_loss4_5_py -.->|imports| ext_PIL
    neurologos_tricameral_loss4_5_py -.->|imports| ext_os
    neurologos_tricameral_loss4_5_py -.->|imports| ext_collections
    neurologos_tricameral_loss4_5_py -.->|imports| ext_torchvision_models
    neurologos_tricameral_loss4_5_py -.->|imports| ext_tqdm
    neurologos_tricameral_loss4_5_py -.->|imports| ext_warnings
    neurologos_tricameral_loss4_5_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss4_5_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss4_5_py -.->|imports| ext_shutil
    neurologos_tricameral_loss5_4_py -.->|imports| ext_os
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_nn
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torchvision_models
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torchaudio
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torchaudio_transforms
    neurologos_tricameral_loss5_4_py -.->|imports| ext_warnings
    neurologos_tricameral_loss5_4_py -.->|imports| ext_kagglehub
    neurologos_tricameral_loss5_4_py -.->|imports| ext_subprocess
    neurologos_tricameral_loss5_4_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss5_4_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss5_4_py -.->|imports| ext_shutil
    neurologos_tricameral_loss5_4_py -.->|imports| ext_soundfile
    neurologos_tricameral_loss5_4_py -.->|imports| ext_time
    neurologos_tricameral_loss5_4_py -.->|imports| ext_numpy
    neurologos_tricameral_loss5_4_py -.->|imports| ext_pathlib
    neurologos_tricameral_loss5_4_py -.->|imports| ext_collections
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torchvision
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss5_4_py -.->|imports| ext_PIL
    neurologos_tricameral_loss5_4_py -.->|imports| ext_tqdm
    neurologos_tricameral_loss5_4_py -.->|imports| ext_functools
    neurologos_tricameral_loss5_4_py -.->|imports| ext_collections
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_nn_functional
    ext_typing["typing"]
    class ext_typing ext;
    neurologos_tricameral_loss5_4_py -.->|imports| ext_typing
    neurologos_tricameral_loss5_4_py -.->|imports| ext_google_colab
    neurologos_tricameral_loss5_4_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss5_4_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss5_4_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss5_4_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss5_4_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss8_0_py -.->|imports| ext_os
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_nn
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torchvision_models
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torchaudio
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torchaudio_transforms
    neurologos_tricameral_loss8_0_py -.->|imports| ext_warnings
    neurologos_tricameral_loss8_0_py -.->|imports| ext_kagglehub
    neurologos_tricameral_loss8_0_py -.->|imports| ext_subprocess
    neurologos_tricameral_loss8_0_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss8_0_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss8_0_py -.->|imports| ext_shutil
    neurologos_tricameral_loss8_0_py -.->|imports| ext_soundfile
    neurologos_tricameral_loss8_0_py -.->|imports| ext_time
    neurologos_tricameral_loss8_0_py -.->|imports| ext_numpy
    neurologos_tricameral_loss8_0_py -.->|imports| ext_pathlib
    neurologos_tricameral_loss8_0_py -.->|imports| ext_collections
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torchvision
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss8_0_py -.->|imports| ext_PIL
    neurologos_tricameral_loss8_0_py -.->|imports| ext_tqdm
    neurologos_tricameral_loss8_0_py -.->|imports| ext_functools
    neurologos_tricameral_loss8_0_py -.->|imports| ext_collections
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_utils_data
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_nn_functional
    neurologos_tricameral_loss8_0_py -.->|imports| ext_typing
    neurologos_tricameral_loss8_0_py -.->|imports| ext_google_colab
    neurologos_tricameral_loss8_0_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss8_0_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss8_0_py -.->|imports| ext_urllib_request
    neurologos_tricameral_loss8_0_py -.->|imports| ext_zipfile
    neurologos_tricameral_loss8_0_py -.->|imports| ext_torch_nn_functional
```

---

## Architecture Reference

### PY (6 files)

#### `app.py`
**Path:** `app.py`

*No symbols extracted*

#### `neurologos_tricameral_loss2.7.py`
**Path:** `neurologos_tricameral_loss2.7.py`

**Classes:**
- `HierarchicalEpisodicMemory` (line 265) `class HierarchicalEpisodicMemory`
- `NeurocognitiveSystem` (line 496) `class NeurocognitiveSystem`
- `LanguageMetrics` (line 693) `class LanguageMetrics` - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 767) `class LinguisticFeedbackLoop`
- `LanguageMetrics` (line 884) `class LanguageMetrics`
- `CausalReasoningEngine` (line 927) `class CausalReasoningEngine`
- `LanguageMetrics` (line 1006) `class LanguageMetrics`
- `StableLiquidNeuron` (line 1053) `class StableLiquidNeuron`
- `TriangulatedMedicalSystem` (line 1192) `class TriangulatedMedicalSystem`
- `LeftHemisphere` (line 1343) `class LeftHemisphere`
- `AudioEncoder` (line 1652) `class AudioEncoder` - *Encoder de audio usando Conv + Transformer*
- `RightHemisphereTricameral` (line 1702) `class RightHemisphereTricameral` - *Hemisferio derecho con canales visual y auditivo*
- `CorpusCallosumTrimodal` (line 1786) `class CorpusCallosumTrimodal`
- `EnhancedDiagnosticsTricameral` (line 1939) `class EnhancedDiagnosticsTricameral`
- `NeuroLogosTricameral` (line 2215) `class NeuroLogosTricameral` - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2250) `class Flickr8kMultimodalDataset(Dataset)` - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `setup_flickr8k_with_audio` (line 53) `def setup_flickr8k_with_audio(data_dir)` - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 241) `def build_vocab_flickr(captions_file, vocab_size)` - *Construye vocabulario desde el archivo de captions*
- `compute_alignment_loss` (line 2354) `def compute_alignment_loss(visual_features, channels, alpha, epoch)` - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2382) `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, lambda_reward, lambda_mtp)`
- `train_tricameral` (line 2429) `def train_tricameral()`
- `__init__` (line 266) `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- `compute_surprise` (line 292) `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- `calculate_importance` (line 302) `def calculate_importance(self, episode, surprise_score)`
- `_calculate_novelty` (line 314) `def _calculate_novelty(self, episode)`
- `store_episode` (line 335) `def store_episode(self, image, audio, caption, surprise_score)`
- `_update_unified_buffer` (line 373) `def _update_unified_buffer(self)`
- `add` (line 385) `def add(self, image, audio, caption, surprise_score)`
- `apply_forgetting_curve` (line 388) `def apply_forgetting_curve(self)`
- `_purge_low_score_memories` (line 404) `def _purge_low_score_memories(self)`
- `sample` (line 430) `def sample(self, batch_size, memory_level)`
- `_sample_from_buffer` (line 460) `def _sample_from_buffer(self, buffer, scores, batch_size)`
- `get_total_size` (line 488) `def get_total_size(self)`
- `__init__` (line 497) `def __init__(self)`
- `assess_reasoning_state` (line 517) `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)` - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 561) `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)` - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 607) `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)` - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 697) `def sentence_bleu(reference, hypothesis, weights)` - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 731) `def _get_ngrams(tokens, n)` - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 740) `def token_accuracy(reference, hypothesis)` - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 753) `def word_overlap(reference, hypothesis)` - *Jaccard similarity entre palabras*
- `__init__` (line 768) `def __init__(self, alpha, beta)`
- `_get_ngrams_cached` (line 782) `def _get_ngrams_cached(sentence, n)` - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 791) `def compute_linguistic_reward(self, references, hypotheses)`
- `compute_cider` (line 830) `def compute_cider(self, reference, hypothesis)` - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 844) `def compute_spice(self, reference, hypothesis)`
- `get_cache_stats` (line 856) `def get_cache_stats(self)` - *FIX: Estadísticas de cache actualizadas*
- `sentence_bleu` (line 886) `def sentence_bleu(reference, hypothesis, weights)`
- `token_accuracy` (line 909) `def token_accuracy(reference, hypothesis)`
- `word_overlap` (line 919) `def word_overlap(reference, hypothesis)`
- `__init__` (line 928) `def __init__(self, hidden_dim)`
- `reason_causally` (line 955) `def reason_causally(self, observation, context)`
- `_predict_interventions` (line 969) `def _predict_interventions(self, hypothesis, confidence)`
- `update_knowledge_graph` (line 986) `def update_knowledge_graph(self, cause, effect, strength)`
- `query_causal_chain` (line 992) `def query_causal_chain(self, start_node, end_node)`
- `sentence_bleu` (line 1008) `def sentence_bleu(reference, hypothesis, weights)`
- `token_accuracy` (line 1031) `def token_accuracy(reference, hypothesis)`
- `word_overlap` (line 1041) `def word_overlap(reference, hypothesis)`
- `__init__` (line 1054) `def __init__(self, in_dim, out_dim)`
- `forward` (line 1096) `def forward(self, x)`
- `_calculate_homeostasis_metric` (line 1112) `def _calculate_homeostasis_metric(self, output)` - *Calcula métrica de homeostasis basada en la estabilidad del output*
- `hebbian_update` (line 1121) `def hebbian_update(self, post, pre, plasticity)`
- `update_physiology_advanced` (line 1159) `def update_physiology_advanced(self, loss_value)`
- `__init__` (line 1193) `def __init__(self)`
- `triangulate_signals` (line 1200) `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- `count_convergent_signals` (line 1211) `def count_convergent_signals(self, signals, pattern)`
- `diagnose_with_triangulation` (line 1214) `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- `apply_triangulated_intervention` (line 1259) `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- `_reset_liquid_neuron` (line 1328) `def _reset_liquid_neuron(self, liquid_neuron)` - *Reset completo de una neurona líquida*
- `__init__` (line 1344) `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- `forward` (line 1426) `def forward(self, visual_context, captions, channels, max_len, epoch)`
- `_apply_chain_of_thought` (line 1473) `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- `_greedy_decode` (line 1513) `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- `_apply_multi_token_prediction` (line 1574) `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- `_apply_structural_attention` (line 1616) `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- `_get_init_state` (line 1637) `def _get_init_state(self, visual_context)`
- `__init__` (line 1655) `def __init__(self, output_dim)`
- `forward` (line 1689) `def forward(self, mel_spec)`
- `__init__` (line 1705) `def __init__(self, output_dim)`
- `forward` (line 1745) `def forward(self, image, audio)` - *Args:
    image: (B, 3, H, W)
    audio: (B, 80, T)
Returns:
    fused_features: (B, output_dim)
    visual_post, visual_pre, audio_post, audio_pre: Para Hebbian*
- `__init__` (line 1787) `def __init__(self, dim)`
- `forward` (line 1835) `def forward(self, right_features)`
- `update_channel_fatigue` (line 1896) `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- `adjust_gates_by_fatigue` (line 1918) `def adjust_gates_by_fatigue(self)`
- `__init__` (line 1940) `def __init__(self)`
- `_get_cached_norm` (line 1962) `def _get_cached_norm(self, tensor, dim)` - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 1980) `def measure_callosal_flow(self, right_features, left_context, channels)`
- `evaluate_reasoning_quality` (line 2010) `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- `calculate_synergy` (line 2047) `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- `calculate_health` (line 2058) `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- `update` (line 2067) `def update(self)`
- `get_recent_avg` (line 2084) `def get_recent_avg(self, key, n)`
- `visualize_fatigue_distribution` (line 2100) `def visualize_fatigue_distribution(self, epoch)`
- `visualize_reasoning_metrics` (line 2124) `def visualize_reasoning_metrics(self, epoch)`
- `report` (line 2136) `def report(self, epoch)`
- `__init__` (line 2218) `def __init__(self, vocab_size)`
- `forward` (line 2224) `def forward(self, image, audio, captions, epoch)`
- `__init__` (line 2253) `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate)`
- `__len__` (line 2301) `def __len__(self)`
- `__getitem__` (line 2305) `def __getitem__(self, idx)`

#### `neurologos_tricameral_loss3.9.py`
**Path:** `neurologos_tricameral_loss3.9.py`

**Classes:**
- `NeurocognitiveSystem` (line 49) `class NeurocognitiveSystem` - *Sistema neurocognitivo que complementa al sistema médico
para optimizar el aprendizaje lingüístico*
- `LinguisticFeedbackLoop` (line 325) `class LinguisticFeedbackLoop` - *Sistema que integra métricas lingüísticas en el proceso de aprendizaje.
Versión optimizada con caché de dos niveles para minimizar cálculos repetitivos.*
- `LanguageMetrics` (line 479) `class LanguageMetrics` - *Métricas de calidad de generación*
- `TriangulatedMedicalSystem` (line 552) `class TriangulatedMedicalSystem` - *Sistema médico con triangulación de señales convergentes*
- `StableLiquidNeuron` (line 827) `class StableLiquidNeuron`
- `RightHemisphere` (line 973) `class RightHemisphere`
- `LeftHemisphere` (line 988) `class LeftHemisphere`
- `CorpusCallosum` (line 1244) `class CorpusCallosum`
- `NeuroLogosBicameralStable` (line 1420) `class NeuroLogosBicameralStable`
- `EnhancedDiagnostics` (line 1446) `class EnhancedDiagnostics`
- `EpisodicMemoryBuffer` (line 1661) `class EpisodicMemoryBuffer`
- `Flickr8kDataset` (line 1708) `class Flickr8kDataset(Dataset)`

**Functions:**
- `compute_loss` (line 20) `def compute_loss(logits, captions, gate, vocab, linguistic_reward, lambda_reward)` - *Función de pérdida extendida que incorpora recompensa lingüística*
- `build_vocab_flickr` (line 1745) `def build_vocab_flickr(captions_file, vocab_size)`
- `setup_flickr8k` (line 1763) `def setup_flickr8k(data_dir)`
- `compute_alignment_loss` (line 1834) `def compute_alignment_loss(visual_features, channels, alpha)` - *Pérdida auxiliar para forzar alineación entre características visuales
y canales estructurales del callosum durante épocas tempranas*
- `train_with_metrics` (line 1858) `def train_with_metrics()`
- `__init__` (line 55) `def __init__(self)`
- `assess_cognitive_state` (line 76) `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)` - *Evalúa el estado cognitivo del modelo basándose en métricas lingüísticas*
- `evaluate_gate_state` (line 124) `def evaluate_gate_state(self, gate_value, current_metrics)` - *MEJORA: Evaluar estado del gate con sistema inmune*
- `update_trauma_memory` (line 142) `def update_trauma_memory(self, gate_value, metrics, outcome)` - *MEJORA: Actualizar memoria traumática basada en resultados*
- `apply_stochastic_perturbation` (line 155) `def apply_stochastic_perturbation(self, model, epoch)` - *MEJORA: Aplicar micro-perturbaciones estocásticas*
- `apply_cognitive_intervention` (line 171) `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)` - *Aplica intervenciones cognitivas basadas en el estado lingüístico*
- `__init__` (line 331) `def __init__(self, alpha, beta)`
- `compute_linguistic_reward` (line 347) `def compute_linguistic_reward(self, references, hypotheses)` - *Calcula una recompensa combinada basada en CIDEr y SPICE.
Utiliza caché para acelerar el cálculo de métricas.*
- `compute_cider` (line 389) `def compute_cider(self, reference, hypothesis)` - *Versión simplificada de CIDEr para uso en entrenamiento.
Optimizada con caché de n-gramas.*
- `compute_spice` (line 427) `def compute_spice(self, reference, hypothesis)` - *Versión simplificada de SPICE para uso en entrenamiento.
Usa Jaccard similarity como proxy semántico.*
- `_get_ngrams` (line 443) `def _get_ngrams(self, sentence, n)` - *Extrae n-gramas de una oración*
- `get_cache_stats` (line 452) `def get_cache_stats(self)` - *Obtiene estadísticas del sistema de caché*
- `sentence_bleu` (line 483) `def sentence_bleu(reference, hypothesis, weights)` - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 517) `def _get_ngrams(tokens, n)` - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 526) `def token_accuracy(reference, hypothesis)` - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 539) `def word_overlap(reference, hypothesis)` - *Jaccard similarity entre palabras*
- `__init__` (line 555) `def __init__(self)`
- `triangulate_signals` (line 560) `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)` - *Identificar señales convergentes que confirman problemas*
- `count_convergent_signals` (line 592) `def count_convergent_signals(self, signals, pattern)` - *Contar cuántas señales del patrón están activas*
- `diagnose_with_triangulation` (line 596) `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)` - *Diagnosticar SOLO con confirmación múltiple*
- `apply_triangulated_intervention` (line 659) `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)` - *Aplicar intervención SOLO si confianza es alta*
- `__init__` (line 828) `def __init__(self, in_dim, out_dim)`
- `forward` (line 871) `def forward(self, x)`
- `hebbian_update` (line 893) `def hebbian_update(self, post, pre, plasticity)`
- `update_physiology_advanced` (line 932) `def update_physiology_advanced(self, loss_value)`
- `__init__` (line 974) `def __init__(self, output_dim)`
- `forward` (line 982) `def forward(self, image)`
- `__init__` (line 989) `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- `beam_search_decode` (line 1066) `def beam_search_decode(self, visual_context, channels, beam_width, max_len, epoch)`
- `forward` (line 1147) `def forward(self, visual_context, captions, channels, max_len, epoch)`
- `_apply_structural_attention` (line 1185) `def _apply_structural_attention(self, lstm_out, channels, visual_context)` - *Aplica atención específica para cada canal estructural (objetos, acciones, escena).
Versión optimizada con matemática robusta y eficiente.*
- `_get_init_state` (line 1230) `def _get_init_state(self, visual_context)`
- `__init__` (line 1245) `def __init__(self, dim)`
- `forward` (line 1308) `def forward(self, right_features, left_features)`
- `update_channel_fatigue` (line 1381) `def update_channel_fatigue(self, objects_channel, actions_channel, scene_channel)` - *MEJORA: Actualizar fatiga específica por canal*
- `adjust_gates_by_fatigue` (line 1404) `def adjust_gates_by_fatigue(self)` - *MEJORA: Ajustar gates basado en fatiga de cada canal*
- `__init__` (line 1421) `def __init__(self, vocab_size)`
- `forward` (line 1427) `def forward(self, image, captions, epoch)`
- `__init__` (line 1447) `def __init__(self)`
- `measure_callosal_flow` (line 1460) `def measure_callosal_flow(self, right_features, left_context, channels)`
- `calculate_synergy` (line 1490) `def calculate_synergy(self, right_node, callosal_flow, left_gate_mean, left_gate_std)`
- `calculate_health` (line 1499) `def calculate_health(self, right_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- `update` (line 1508) `def update(self)`
- `get_recent_avg` (line 1519) `def get_recent_avg(self, key, n)`
- `visualize_fatigue_distribution` (line 1538) `def visualize_fatigue_distribution(self, epoch)` - *MEJORA: Visualizar distribución de fatiga entre canales*
- `report` (line 1567) `def report(self, epoch)`
- `__init__` (line 1662) `def __init__(self, capacity, surprise_threshold)`
- `compute_surprise` (line 1668) `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- `add` (line 1679) `def add(self, image, caption, surprise_score)`
- `sample` (line 1689) `def sample(self, batch_size)`
- `__init__` (line 1709) `def __init__(self, images_dir, captions_file, vocab, transform, max_len)`
- `__len__` (line 1726) `def __len__(self)`
- `__getitem__` (line 1729) `def __getitem__(self, idx)`

#### `neurologos_tricameral_loss4.5.py`
**Path:** `neurologos_tricameral_loss4.5.py`

**Classes:**
- `LanguageMetrics` (line 44) `class LanguageMetrics` - *Métricas de calidad de generación*
- `TriangulatedMedicalSystem` (line 117) `class TriangulatedMedicalSystem` - *Sistema médico con triangulación de señales convergentes*
- `StableLiquidNeuron` (line 392) `class StableLiquidNeuron`
- `RightHemisphere` (line 518) `class RightHemisphere`
- `LeftHemisphere` (line 533) `class LeftHemisphere`
- `CorpusCallosum` (line 709) `class CorpusCallosum`
- `NeuroLogosBicameralStable` (line 765) `class NeuroLogosBicameralStable`
- `EnhancedDiagnostics` (line 786) `class EnhancedDiagnostics`
- `EpisodicMemoryBuffer` (line 907) `class EpisodicMemoryBuffer`
- `Flickr8kDataset` (line 954) `class Flickr8kDataset(Dataset)`

**Functions:**
- `compute_loss` (line 20) `def compute_loss(logits, captions, gate, vocab)`
- `build_vocab_flickr` (line 991) `def build_vocab_flickr(captions_file, vocab_size)`
- `setup_flickr8k` (line 1009) `def setup_flickr8k(data_dir)`
- `train_with_metrics` (line 1081) `def train_with_metrics()`
- `sentence_bleu` (line 48) `def sentence_bleu(reference, hypothesis, weights)` - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 82) `def _get_ngrams(tokens, n)` - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 91) `def token_accuracy(reference, hypothesis)` - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 104) `def word_overlap(reference, hypothesis)` - *Jaccard similarity entre palabras*
- `__init__` (line 120) `def __init__(self)`
- `triangulate_signals` (line 125) `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)` - *Identificar señales convergentes que confirman problemas*
- `count_convergent_signals` (line 157) `def count_convergent_signals(self, signals, pattern)` - *Contar cuántas señales del patrón están activas*
- `diagnose_with_triangulation` (line 161) `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)` - *Diagnosticar SOLO con confirmación múltiple*
- `apply_triangulated_intervention` (line 224) `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)` - *Aplicar intervención SOLO si confianza es alta*
- `__init__` (line 393) `def __init__(self, in_dim, out_dim)`
- `forward` (line 431) `def forward(self, x)`
- `hebbian_update` (line 453) `def hebbian_update(self, post, pre, plasticity)`
- `update_physiology_advanced` (line 492) `def update_physiology_advanced(self, loss_value)`
- `__init__` (line 519) `def __init__(self, output_dim)`
- `forward` (line 527) `def forward(self, image)`
- `__init__` (line 534) `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- `beam_search_decode` (line 584) `def beam_search_decode(self, visual_context, beam_width, max_len, epoch)`
- `forward` (line 657) `def forward(self, visual_context, captions, max_len, epoch)`
- `_get_init_state` (line 695) `def _get_init_state(self, visual_context)`
- `__init__` (line 710) `def __init__(self, dim)`
- `forward` (line 742) `def forward(self, right_features)`
- `__init__` (line 766) `def __init__(self, vocab_size)`
- `forward` (line 772) `def forward(self, image, captions, epoch)`
- `__init__` (line 787) `def __init__(self)`
- `measure_callosal_flow` (line 797) `def measure_callosal_flow(self, right_features, left_context)`
- `calculate_synergy` (line 806) `def calculate_synergy(self, right_node, callosal_flow, left_gate_mean, left_gate_std)`
- `calculate_health` (line 815) `def calculate_health(self, right_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- `update` (line 824) `def update(self)`
- `get_recent_avg` (line 829) `def get_recent_avg(self, key, n)`
- `report` (line 834) `def report(self, epoch)`
- `__init__` (line 908) `def __init__(self, capacity, surprise_threshold)`
- `compute_surprise` (line 914) `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- `add` (line 925) `def add(self, image, caption, surprise_score)`
- `sample` (line 935) `def sample(self, batch_size)`
- `__init__` (line 955) `def __init__(self, images_dir, captions_file, vocab, transform, max_len)`
- `__len__` (line 972) `def __len__(self)`
- `__getitem__` (line 975) `def __getitem__(self, idx)`

#### `neurologos_tricameral_loss5.4.py`
**Path:** `neurologos_tricameral_loss5.4.py`

**Classes:**
- `HierarchicalEpisodicMemory` (line 340) `class HierarchicalEpisodicMemory` - *Memoria episódica optimizada con estabilización numérica en sampling
- Fixed: Clamp de surprise scores para evitar probabilidades degeneradas
- Fixed: Verificación explícita de NaN en operaciones de buffer*
- `NeurocognitiveSystem` (line 577) `class NeurocognitiveSystem`
- `LanguageMetrics` (line 774) `class LanguageMetrics` - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 848) `class LinguisticFeedbackLoop`
- `LanguageMetrics` (line 965) `class LanguageMetrics`
- `CausalReasoningEngine` (line 1008) `class CausalReasoningEngine`
- `LanguageMetrics` (line 1087) `class LanguageMetrics`
- `StableLiquidNeuron` (line 1134) `class StableLiquidNeuron`
- `TricameralOutput` (line 1321) `class TricameralOutput(NamedTuple)`
- `TriangulatedMedicalSystem` (line 1360) `class TriangulatedMedicalSystem`
- `LeftHemisphere` (line 1510) `class LeftHemisphere`
- `AudioEncoder` (line 1833) `class AudioEncoder` - *Encoder de audio optimizado con:
- Pruning estructurado en canales Conv (30% reducción)
- Gradient checkpointing para memoria de activaciones
- Preparación para QAT INT8*
- `RightHemisphereTricameral` (line 1901) `class RightHemisphereTricameral` - *Hemisferio derecho optimizado:
- Gradient checkpointing obligatorio en ResNet50
- AudioEncoder con canales reducidos (90-180-360)
- Memoria activaciones reducida en 60%*
- `CorpusCallosumTrimodal` (line 1984) `class CorpusCallosumTrimodal` - *Corpus Callosum optimizado con:
- Dimensión base reducida: 512→320 dims (-37.5%)
- Bottleneck compartido para 3 canales (1 Linear vs 3 ModuleList)
- Flash Attention / xFormers compatible
- Gates fusionados en tensor único
Reducción: 2.1M → 0.88M parámetros (-58%)*
- `EnhancedDiagnosticsTricameral` (line 2207) `class EnhancedDiagnosticsTricameral`
- `NeuroLogosTricameral` (line 2515) `class NeuroLogosTricameral` - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2550) `class Flickr8kMultimodalDataset(Dataset)` - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `preprocess_and_cache_spectrograms` (line 49) `def preprocess_and_cache_spectrograms(audio_dir, cache_dir, sample_rate, target_len)` - *Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt
Esto elimina el cuello de botella de I/O durante entrenamiento*
- `apply_emergency_fixes` (line 120) `def apply_emergency_fixes(model)`
- `setup_flickr8k_with_audio` (line 142) `def setup_flickr8k_with_audio(data_dir)` - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 316) `def build_vocab_flickr(captions_file, vocab_size)` - *Construye vocabulario desde el archivo de captions*
- `forward` (line 1335) `def forward(self, image, audio, captions, epoch)`
- `compute_alignment_loss` (line 2666) `def compute_alignment_loss(visual_features, channels, alpha, epoch)` - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2695) `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, channels, epoch, lambda_reward, lambda_mtp)`
- `train_tricameral` (line 2812) `def train_tricameral()`
- `__init__` (line 347) `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- `compute_surprise` (line 371) `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)` - *FIX: Clamp de cross-entropy para evitar infinitos*
- `calculate_importance` (line 386) `def calculate_importance(self, episode, surprise_score)` - *FIX: Clamp de surprise_score para evitar probabilidades degeneradas*
- `_calculate_novelty` (line 402) `def _calculate_novelty(self, episode)` - *FIX: Manejo de edge case cuando no hay memorias*
- `store_episode` (line 427) `def store_episode(self, image, audio, caption, surprise_score)`
- `_update_unified_buffer` (line 456) `def _update_unified_buffer(self)` - *FIX: Verificar integridad de scores antes de unificar*
- `sample` (line 470) `def sample(self, batch_size, memory_level)` - *FIX: Manejo de edge cases en sampling probabilístico*
- `_sample_from_buffer` (line 494) `def _sample_from_buffer(self, buffer, scores, batch_size)` - *FIX: Estabilización completa de probabilidades de sampling*
- `apply_forgetting_curve` (line 535) `def apply_forgetting_curve(self)`
- `_purge_low_score_memories` (line 545) `def _purge_low_score_memories(self)` - *FIX: Purga con threshold ajustado y verificación de scores*
- `__init__` (line 578) `def __init__(self)`
- `assess_reasoning_state` (line 598) `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)` - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 642) `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)` - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 688) `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)` - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 778) `def sentence_bleu(reference, hypothesis, weights)` - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 812) `def _get_ngrams(tokens, n)` - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 821) `def token_accuracy(reference, hypothesis)` - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 834) `def word_overlap(reference, hypothesis)` - *Jaccard similarity entre palabras*
- `__init__` (line 849) `def __init__(self, alpha, beta)`
- `_get_ngrams_cached` (line 863) `def _get_ngrams_cached(sentence, n)` - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 872) `def compute_linguistic_reward(self, references, hypotheses)`
- `compute_cider` (line 911) `def compute_cider(self, reference, hypothesis)` - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 925) `def compute_spice(self, reference, hypothesis)`
- `get_cache_stats` (line 937) `def get_cache_stats(self)` - *FIX: Estadísticas de cache actualizadas*
- `sentence_bleu` (line 967) `def sentence_bleu(reference, hypothesis, weights)`
- `token_accuracy` (line 990) `def token_accuracy(reference, hypothesis)`
- `word_overlap` (line 1000) `def word_overlap(reference, hypothesis)`
- `__init__` (line 1009) `def __init__(self, hidden_dim)`
- `reason_causally` (line 1036) `def reason_causally(self, observation, context)`
- `_predict_interventions` (line 1050) `def _predict_interventions(self, hypothesis, confidence)`
- `update_knowledge_graph` (line 1067) `def update_knowledge_graph(self, cause, effect, strength)`
- `query_causal_chain` (line 1073) `def query_causal_chain(self, start_node, end_node)`
- `sentence_bleu` (line 1089) `def sentence_bleu(reference, hypothesis, weights)`
- `token_accuracy` (line 1112) `def token_accuracy(reference, hypothesis)`
- `word_overlap` (line 1122) `def word_overlap(reference, hypothesis)`
- `__init__` (line 1136) `def __init__(self, in_dim, out_dim)`
- `forward` (line 1184) `def forward(self, x)`
- `_calculate_homeostasis_metric` (line 1219) `def _calculate_homeostasis_metric(self, output)` - *Calcula métrica de homeostasis con estabilización numérica*
- `hebbian_update` (line 1229) `def hebbian_update(self, post, pre, plasticity)`
- `update_physiology_advanced` (line 1278) `def update_physiology_advanced(self, loss_value)`
- `__init__` (line 1361) `def __init__(self)`
- `triangulate_signals` (line 1368) `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- `count_convergent_signals` (line 1379) `def count_convergent_signals(self, signals, pattern)`
- `diagnose_with_triangulation` (line 1382) `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- `apply_triangulated_intervention` (line 1427) `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- `_reset_liquid_neuron` (line 1496) `def _reset_liquid_neuron(self, liquid_neuron)`
- `__init__` (line 1511) `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- `forward` (line 1596) `def forward(self, visual_context, captions, channels, max_len, epoch)`
- `_apply_chain_of_thought` (line 1653) `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- `_apply_multi_token_prediction` (line 1694) `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- `_apply_structural_attention` (line 1737) `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- `_greedy_decode` (line 1759) `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- `_get_init_state` (line 1819) `def _get_init_state(self, visual_context)`
- `__init__` (line 1842) `def __init__(self, output_dim)`
- `forward` (line 1880) `def forward(self, mel_spec)`
- `__init__` (line 1909) `def __init__(self, output_dim)`
- `forward` (line 1947) `def forward(self, image, audio)`
- `__init__` (line 1994) `def __init__(self, dim)`
- `_apply_flash_attention` (line 2057) `def _apply_flash_attention(self, x)` - *Aplica Flash Attention nativa de PyTorch 2.0+
FIX: Corrección de dimensiones para seq_len variable*
- `forward` (line 2090) `def forward(self, right_features)` - *FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal*
- `update_channel_fatigue` (line 2169) `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- `adjust_gates_by_fatigue` (line 2190) `def adjust_gates_by_fatigue(self)` - *Lógica original de ajuste de gates*
- `__init__` (line 2208) `def __init__(self)`
- `_get_cached_norm` (line 2231) `def _get_cached_norm(self, tensor, dim)` - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 2248) `def measure_callosal_flow(self, right_features, left_context, channels)` - *Medición de coherencia multimodal con sincronización entre canales*
- `evaluate_reasoning_quality` (line 2305) `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- `calculate_synergy` (line 2342) `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- `calculate_health` (line 2353) `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- `update` (line 2362) `def update(self)`
- `get_recent_avg` (line 2379) `def get_recent_avg(self, key, n)`
- `visualize_fatigue_distribution` (line 2395) `def visualize_fatigue_distribution(self, epoch)`
- `visualize_reasoning_metrics` (line 2417) `def visualize_reasoning_metrics(self, epoch)`
- `report` (line 2429) `def report(self, epoch)`
- `__init__` (line 2518) `def __init__(self, vocab_size)`
- `forward` (line 2525) `def forward(self, image, audio, captions, epoch)`
- `__init__` (line 2553) `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate, use_cache, cache_dir)`
- `__len__` (line 2610) `def __len__(self)`
- `__getitem__` (line 2613) `def __getitem__(self, idx)`

#### `neurologos_tricameral_loss8.0.py`
**Path:** `neurologos_tricameral_loss8.0.py`

**Classes:**
- `HierarchicalEpisodicMemory` (line 342) `class HierarchicalEpisodicMemory` - *Memoria episódica optimizada con estabilización numérica en sampling
- Fixed: Clamp de surprise scores para evitar probabilidades degeneradas
- Fixed: Verificación explícita de NaN en operaciones de buffer*
- `NeurocognitiveSystem` (line 581) `class NeurocognitiveSystem`
- `LanguageMetrics` (line 778) `class LanguageMetrics` - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 852) `class LinguisticFeedbackLoop`
- `CausalReasoningEngine` (line 968) `class CausalReasoningEngine`
- `StableLiquidNeuron` (line 1048) `class StableLiquidNeuron`
- `TricameralOutput` (line 1235) `class TricameralOutput(NamedTuple)`
- `TriangulatedMedicalSystem` (line 1274) `class TriangulatedMedicalSystem`
- `LeftHemisphere` (line 1424) `class LeftHemisphere`
- `AudioEncoder` (line 1748) `class AudioEncoder` - *Encoder de audio optimizado con:
- Pruning estructurado en canales Conv (30% reducción)
- Gradient checkpointing para memoria de activaciones
- Preparación para QAT INT8*
- `RightHemisphereTricameral` (line 1816) `class RightHemisphereTricameral` - *Hemisferio derecho optimizado:
- Gradient checkpointing obligatorio en ResNet50
- AudioEncoder con canales reducidos (90-180-360)
- Memoria activaciones reducida en 60%*
- `CorpusCallosumTrimodal` (line 1899) `class CorpusCallosumTrimodal` - *Corpus Callosum optimizado con:
- Dimensión base reducida: 512→320 dims (-37.5%)
- Bottleneck compartido para 3 canales (1 Linear vs 3 ModuleList)
- Flash Attention / xFormers compatible
- Gates fusionados en tensor único
Reducción: 2.1M → 0.88M parámetros (-58%)*
- `EnhancedDiagnosticsTricameral` (line 2122) `class EnhancedDiagnosticsTricameral`
- `NeuroLogosTricameral` (line 2430) `class NeuroLogosTricameral` - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2465) `class Flickr8kMultimodalDataset(Dataset)` - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `preprocess_and_cache_spectrograms` (line 49) `def preprocess_and_cache_spectrograms(audio_dir, cache_dir, sample_rate, target_len)` - *Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt
Esto elimina el cuello de botella de I/O durante entrenamiento*
- `apply_emergency_fixes` (line 122) `def apply_emergency_fixes(model)`
- `setup_flickr8k_with_audio` (line 144) `def setup_flickr8k_with_audio(data_dir)` - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 318) `def build_vocab_flickr(captions_file, vocab_size)` - *Construye vocabulario desde el archivo de captions*
- `forward` (line 1249) `def forward(self, image, audio, captions, epoch)`
- `compute_alignment_loss` (line 2581) `def compute_alignment_loss(visual_features, channels, alpha, epoch)` - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2610) `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, channels, epoch, lambda_reward, lambda_mtp)`
- `train_tricameral` (line 2727) `def train_tricameral()`
- `__init__` (line 349) `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- `compute_surprise` (line 373) `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)` - *FIX: Clamp de cross-entropy para evitar infinitos*
- `calculate_importance` (line 388) `def calculate_importance(self, episode, surprise_score)` - *FIX: Clamp de surprise_score para evitar probabilidades degeneradas*
- `_calculate_novelty` (line 404) `def _calculate_novelty(self, episode)` - *FIX: Manejo de edge case cuando no hay memorias*
- `store_episode` (line 429) `def store_episode(self, image, audio, caption, surprise_score)`
- `_update_unified_buffer` (line 460) `def _update_unified_buffer(self)` - *FIX: Verificar integridad de scores antes de unificar*
- `sample` (line 474) `def sample(self, batch_size, memory_level)` - *FIX: Manejo de edge cases en sampling probabilístico*
- `_sample_from_buffer` (line 498) `def _sample_from_buffer(self, buffer, scores, batch_size)` - *FIX: Estabilización completa de probabilidades de sampling*
- `apply_forgetting_curve` (line 539) `def apply_forgetting_curve(self)`
- `_purge_low_score_memories` (line 549) `def _purge_low_score_memories(self)` - *FIX: Purga con threshold ajustado y verificación de scores*
- `__init__` (line 582) `def __init__(self)`
- `assess_reasoning_state` (line 602) `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)` - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 646) `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)` - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 692) `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)` - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 782) `def sentence_bleu(reference, hypothesis, weights)` - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 816) `def _get_ngrams(tokens, n)` - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 825) `def token_accuracy(reference, hypothesis)` - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 838) `def word_overlap(reference, hypothesis)` - *Jaccard similarity entre palabras*
- `__init__` (line 853) `def __init__(self, alpha, beta)`
- `_get_ngrams_cached` (line 867) `def _get_ngrams_cached(sentence, n)` - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 876) `def compute_linguistic_reward(self, references, hypotheses)`
- `compute_cider` (line 915) `def compute_cider(self, reference, hypothesis)` - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 929) `def compute_spice(self, reference, hypothesis)`
- `get_cache_stats` (line 941) `def get_cache_stats(self)` - *FIX: Estadísticas de cache actualizadas*
- `__init__` (line 969) `def __init__(self, hidden_dim)`
- `reason_causally` (line 996) `def reason_causally(self, observation, context)`
- `_predict_interventions` (line 1010) `def _predict_interventions(self, hypothesis, confidence)`
- `update_knowledge_graph` (line 1027) `def update_knowledge_graph(self, cause, effect, strength)`
- `query_causal_chain` (line 1033) `def query_causal_chain(self, start_node, end_node)`
- `__init__` (line 1050) `def __init__(self, in_dim, out_dim)`
- `forward` (line 1098) `def forward(self, x)`
- `_calculate_homeostasis_metric` (line 1133) `def _calculate_homeostasis_metric(self, output)` - *Calcula métrica de homeostasis con estabilización numérica*
- `hebbian_update` (line 1143) `def hebbian_update(self, post, pre, plasticity)`
- `update_physiology_advanced` (line 1192) `def update_physiology_advanced(self, loss_value)`
- `__init__` (line 1275) `def __init__(self)`
- `triangulate_signals` (line 1282) `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- `count_convergent_signals` (line 1293) `def count_convergent_signals(self, signals, pattern)`
- `diagnose_with_triangulation` (line 1296) `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- `apply_triangulated_intervention` (line 1341) `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- `_reset_liquid_neuron` (line 1410) `def _reset_liquid_neuron(self, liquid_neuron)`
- `__init__` (line 1425) `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- `forward` (line 1512) `def forward(self, visual_context, captions, channels, max_len, epoch)`
- `_apply_chain_of_thought` (line 1567) `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- `_apply_multi_token_prediction` (line 1608) `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- `_apply_structural_attention` (line 1652) `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- `_greedy_decode` (line 1674) `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- `_get_init_state` (line 1734) `def _get_init_state(self, visual_context)`
- `__init__` (line 1757) `def __init__(self, output_dim)`
- `forward` (line 1795) `def forward(self, mel_spec)`
- `__init__` (line 1824) `def __init__(self, output_dim)`
- `forward` (line 1862) `def forward(self, image, audio)`
- `__init__` (line 1909) `def __init__(self, dim)`
- `_apply_flash_attention` (line 1972) `def _apply_flash_attention(self, x)` - *Aplica Flash Attention nativa de PyTorch 2.0+
FIX: Corrección de dimensiones para seq_len variable*
- `forward` (line 2005) `def forward(self, right_features)` - *FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal*
- `update_channel_fatigue` (line 2084) `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- `adjust_gates_by_fatigue` (line 2105) `def adjust_gates_by_fatigue(self)` - *Lógica original de ajuste de gates*
- `__init__` (line 2123) `def __init__(self)`
- `_get_cached_norm` (line 2146) `def _get_cached_norm(self, tensor, dim)` - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 2163) `def measure_callosal_flow(self, right_features, left_context, channels)` - *Medición de coherencia multimodal con sincronización entre canales*
- `evaluate_reasoning_quality` (line 2220) `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- `calculate_synergy` (line 2257) `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- `calculate_health` (line 2268) `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- `update` (line 2277) `def update(self)`
- `get_recent_avg` (line 2294) `def get_recent_avg(self, key, n)`
- `visualize_fatigue_distribution` (line 2310) `def visualize_fatigue_distribution(self, epoch)`
- `visualize_reasoning_metrics` (line 2332) `def visualize_reasoning_metrics(self, epoch)`
- `report` (line 2344) `def report(self, epoch)`
- `__init__` (line 2433) `def __init__(self, vocab_size)`
- `forward` (line 2440) `def forward(self, image, audio, captions, epoch)`
- `__init__` (line 2468) `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate, use_cache, cache_dir)`
- `__len__` (line 2525) `def __len__(self)`
- `__getitem__` (line 2528) `def __getitem__(self, idx)`

### SH (1 files)

#### `install.sh`
**Path:** `install.sh`

*No symbols extracted*
