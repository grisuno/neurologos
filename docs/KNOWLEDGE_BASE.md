# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis.

**Total Files Parsed:** 7 | **Total Symbols Extracted:** 419 | **Total Imports:** 127

## Structural Knowledge Map
```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray: 5 5,color:#aaa;
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

**Classs:**
- `HierarchicalEpisodicMemory` (line 265)
- `NeurocognitiveSystem` (line 496)
- `LanguageMetrics` (line 693) - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 767)
- `LanguageMetrics` (line 884)
- `CausalReasoningEngine` (line 927)
- `LanguageMetrics` (line 1006)
- `StableLiquidNeuron` (line 1053)
- `TriangulatedMedicalSystem` (line 1192)
- `LeftHemisphere` (line 1343)
- `AudioEncoder` (line 1652) - *Encoder de audio usando Conv + Transformer*
- `RightHemisphereTricameral` (line 1702) - *Hemisferio derecho con canales visual y auditivo*
- `CorpusCallosumTrimodal` (line 1786)
- `EnhancedDiagnosticsTricameral` (line 1939)
- `NeuroLogosTricameral` (line 2215) - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2250) - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `setup_flickr8k_with_audio` (line 53) - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 241) - *Construye vocabulario desde el archivo de captions*
- `compute_alignment_loss` (line 2354) - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2382)
- `train_tricameral` (line 2429)
- `__init__` (line 266)
- `compute_surprise` (line 292)
- `calculate_importance` (line 302)
- `_calculate_novelty` (line 314)
- `store_episode` (line 335)
- `_update_unified_buffer` (line 373)
- `add` (line 385)
- `apply_forgetting_curve` (line 388)
- `_purge_low_score_memories` (line 404)
- `sample` (line 430)
- `_sample_from_buffer` (line 460)
- `get_total_size` (line 488)
- `__init__` (line 497)
- `assess_reasoning_state` (line 517) - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 561) - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 607) - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 697) - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 731) - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 740) - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 753) - *Jaccard similarity entre palabras*
- `__init__` (line 768)
- `_get_ngrams_cached` (line 782) - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 791)
- `compute_cider` (line 830) - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 844)
- `get_cache_stats` (line 856) - *FIX: Estadísticas de cache actualizadas*
- `sentence_bleu` (line 886)
- `token_accuracy` (line 909)
- `word_overlap` (line 919)
- `__init__` (line 928)
- `reason_causally` (line 955)
- `_predict_interventions` (line 969)
- `update_knowledge_graph` (line 986)
- `query_causal_chain` (line 992)
- `sentence_bleu` (line 1008)
- `token_accuracy` (line 1031)
- `word_overlap` (line 1041)
- `__init__` (line 1054)
- `forward` (line 1096)
- `_calculate_homeostasis_metric` (line 1112) - *Calcula métrica de homeostasis basada en la estabilidad del output*
- `hebbian_update` (line 1121)
- `update_physiology_advanced` (line 1159)
- `__init__` (line 1193)
- `triangulate_signals` (line 1200)
- `count_convergent_signals` (line 1211)
- `diagnose_with_triangulation` (line 1214)
- `apply_triangulated_intervention` (line 1259)
- `_reset_liquid_neuron` (line 1328) - *Reset completo de una neurona líquida*
- `__init__` (line 1344)
- `forward` (line 1426)
- `_apply_chain_of_thought` (line 1473)
- `_greedy_decode` (line 1513)
- `_apply_multi_token_prediction` (line 1574)
- `_apply_structural_attention` (line 1616)
- `_get_init_state` (line 1637)
- `__init__` (line 1655)
- `forward` (line 1689)
- `__init__` (line 1705)
- `forward` (line 1745) - *Args:
    image: (B, 3, H, W)
    audio: (B, 80, T)
Returns:
    fused_features: (B, output_dim)
    visual_post, visual_pre, audio_post, audio_pre: Para Hebbian*
- `__init__` (line 1787)
- `forward` (line 1835)
- `update_channel_fatigue` (line 1896)
- `adjust_gates_by_fatigue` (line 1918)
- `__init__` (line 1940)
- `_get_cached_norm` (line 1962) - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 1980)
- `evaluate_reasoning_quality` (line 2010)
- `calculate_synergy` (line 2047)
- `calculate_health` (line 2058)
- `update` (line 2067)
- `get_recent_avg` (line 2084)
- `visualize_fatigue_distribution` (line 2100)
- `visualize_reasoning_metrics` (line 2124)
- `report` (line 2136)
- `__init__` (line 2218)
- `forward` (line 2224)
- `__init__` (line 2253)
- `__len__` (line 2301)
- `__getitem__` (line 2305)

#### `neurologos_tricameral_loss3.9.py`
**Path:** `neurologos_tricameral_loss3.9.py`

**Classs:**
- `NeurocognitiveSystem` (line 49) - *Sistema neurocognitivo que complementa al sistema médico
para optimizar el aprendizaje lingüístico*
- `LinguisticFeedbackLoop` (line 325) - *Sistema que integra métricas lingüísticas en el proceso de aprendizaje.
Versión optimizada con caché de dos niveles para minimizar cálculos repetitivos.*
- `LanguageMetrics` (line 479) - *Métricas de calidad de generación*
- `TriangulatedMedicalSystem` (line 552) - *Sistema médico con triangulación de señales convergentes*
- `StableLiquidNeuron` (line 827)
- `RightHemisphere` (line 973)
- `LeftHemisphere` (line 988)
- `CorpusCallosum` (line 1244)
- `NeuroLogosBicameralStable` (line 1420)
- `EnhancedDiagnostics` (line 1446)
- `EpisodicMemoryBuffer` (line 1661)
- `Flickr8kDataset` (line 1708)

**Functions:**
- `compute_loss` (line 20) - *Función de pérdida extendida que incorpora recompensa lingüística*
- `build_vocab_flickr` (line 1745)
- `setup_flickr8k` (line 1763)
- `compute_alignment_loss` (line 1834) - *Pérdida auxiliar para forzar alineación entre características visuales
y canales estructurales del callosum durante épocas tempranas*
- `train_with_metrics` (line 1858)
- `__init__` (line 55)
- `assess_cognitive_state` (line 76) - *Evalúa el estado cognitivo del modelo basándose en métricas lingüísticas*
- `evaluate_gate_state` (line 124) - *MEJORA: Evaluar estado del gate con sistema inmune*
- `update_trauma_memory` (line 142) - *MEJORA: Actualizar memoria traumática basada en resultados*
- `apply_stochastic_perturbation` (line 155) - *MEJORA: Aplicar micro-perturbaciones estocásticas*
- `apply_cognitive_intervention` (line 171) - *Aplica intervenciones cognitivas basadas en el estado lingüístico*
- `__init__` (line 331)
- `compute_linguistic_reward` (line 347) - *Calcula una recompensa combinada basada en CIDEr y SPICE.
Utiliza caché para acelerar el cálculo de métricas.*
- `compute_cider` (line 389) - *Versión simplificada de CIDEr para uso en entrenamiento.
Optimizada con caché de n-gramas.*
- `compute_spice` (line 427) - *Versión simplificada de SPICE para uso en entrenamiento.
Usa Jaccard similarity como proxy semántico.*
- `_get_ngrams` (line 443) - *Extrae n-gramas de una oración*
- `get_cache_stats` (line 452) - *Obtiene estadísticas del sistema de caché*
- `sentence_bleu` (line 483) - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 517) - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 526) - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 539) - *Jaccard similarity entre palabras*
- `__init__` (line 555)
- `triangulate_signals` (line 560) - *Identificar señales convergentes que confirman problemas*
- `count_convergent_signals` (line 592) - *Contar cuántas señales del patrón están activas*
- `diagnose_with_triangulation` (line 596) - *Diagnosticar SOLO con confirmación múltiple*
- `apply_triangulated_intervention` (line 659) - *Aplicar intervención SOLO si confianza es alta*
- `__init__` (line 828)
- `forward` (line 871)
- `hebbian_update` (line 893)
- `update_physiology_advanced` (line 932)
- `__init__` (line 974)
- `forward` (line 982)
- `__init__` (line 989)
- `beam_search_decode` (line 1066)
- `forward` (line 1147)
- `_apply_structural_attention` (line 1185) - *Aplica atención específica para cada canal estructural (objetos, acciones, escena).
Versión optimizada con matemática robusta y eficiente.*
- `_get_init_state` (line 1230)
- `__init__` (line 1245)
- `forward` (line 1308)
- `update_channel_fatigue` (line 1381) - *MEJORA: Actualizar fatiga específica por canal*
- `adjust_gates_by_fatigue` (line 1404) - *MEJORA: Ajustar gates basado en fatiga de cada canal*
- `__init__` (line 1421)
- `forward` (line 1427)
- `__init__` (line 1447)
- `measure_callosal_flow` (line 1460)
- `calculate_synergy` (line 1490)
- `calculate_health` (line 1499)
- `update` (line 1508)
- `get_recent_avg` (line 1519)
- `visualize_fatigue_distribution` (line 1538) - *MEJORA: Visualizar distribución de fatiga entre canales*
- `report` (line 1567)
- `__init__` (line 1662)
- `compute_surprise` (line 1668)
- `add` (line 1679)
- `sample` (line 1689)
- `__init__` (line 1709)
- `__len__` (line 1726)
- `__getitem__` (line 1729)

#### `neurologos_tricameral_loss4.5.py`
**Path:** `neurologos_tricameral_loss4.5.py`

**Classs:**
- `LanguageMetrics` (line 44) - *Métricas de calidad de generación*
- `TriangulatedMedicalSystem` (line 117) - *Sistema médico con triangulación de señales convergentes*
- `StableLiquidNeuron` (line 392)
- `RightHemisphere` (line 518)
- `LeftHemisphere` (line 533)
- `CorpusCallosum` (line 709)
- `NeuroLogosBicameralStable` (line 765)
- `EnhancedDiagnostics` (line 786)
- `EpisodicMemoryBuffer` (line 907)
- `Flickr8kDataset` (line 954)

**Functions:**
- `compute_loss` (line 20)
- `build_vocab_flickr` (line 991)
- `setup_flickr8k` (line 1009)
- `train_with_metrics` (line 1081)
- `sentence_bleu` (line 48) - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 82) - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 91) - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 104) - *Jaccard similarity entre palabras*
- `__init__` (line 120)
- `triangulate_signals` (line 125) - *Identificar señales convergentes que confirman problemas*
- `count_convergent_signals` (line 157) - *Contar cuántas señales del patrón están activas*
- `diagnose_with_triangulation` (line 161) - *Diagnosticar SOLO con confirmación múltiple*
- `apply_triangulated_intervention` (line 224) - *Aplicar intervención SOLO si confianza es alta*
- `__init__` (line 393)
- `forward` (line 431)
- `hebbian_update` (line 453)
- `update_physiology_advanced` (line 492)
- `__init__` (line 519)
- `forward` (line 527)
- `__init__` (line 534)
- `beam_search_decode` (line 584)
- `forward` (line 657)
- `_get_init_state` (line 695)
- `__init__` (line 710)
- `forward` (line 742)
- `__init__` (line 766)
- `forward` (line 772)
- `__init__` (line 787)
- `measure_callosal_flow` (line 797)
- `calculate_synergy` (line 806)
- `calculate_health` (line 815)
- `update` (line 824)
- `get_recent_avg` (line 829)
- `report` (line 834)
- `__init__` (line 908)
- `compute_surprise` (line 914)
- `add` (line 925)
- `sample` (line 935)
- `__init__` (line 955)
- `__len__` (line 972)
- `__getitem__` (line 975)

#### `neurologos_tricameral_loss5.4.py`
**Path:** `neurologos_tricameral_loss5.4.py`

**Classs:**
- `HierarchicalEpisodicMemory` (line 340) - *Memoria episódica optimizada con estabilización numérica en sampling
- Fixed: Clamp de surprise scores para evitar probabilidades degeneradas
- Fixed: Verificación explícita de NaN en operaciones de buffer*
- `NeurocognitiveSystem` (line 577)
- `LanguageMetrics` (line 774) - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 848)
- `LanguageMetrics` (line 965)
- `CausalReasoningEngine` (line 1008)
- `LanguageMetrics` (line 1087)
- `StableLiquidNeuron` (line 1134)
- `TricameralOutput` (line 1321)
- `TriangulatedMedicalSystem` (line 1360)
- `LeftHemisphere` (line 1510)
- `AudioEncoder` (line 1833) - *Encoder de audio optimizado con:
- Pruning estructurado en canales Conv (30% reducción)
- Gradient checkpointing para memoria de activaciones
- Preparación para QAT INT8*
- `RightHemisphereTricameral` (line 1901) - *Hemisferio derecho optimizado:
- Gradient checkpointing obligatorio en ResNet50
- AudioEncoder con canales reducidos (90-180-360)
- Memoria activaciones reducida en 60%*
- `CorpusCallosumTrimodal` (line 1984) - *Corpus Callosum optimizado con:
- Dimensión base reducida: 512→320 dims (-37.5%)
- Bottleneck compartido para 3 canales (1 Linear vs 3 ModuleList)
- Flash Attention / xFormers compatible
- Gates fusionados en tensor único
Reducción: 2.1M → 0.88M parámetros (-58%)*
- `EnhancedDiagnosticsTricameral` (line 2207)
- `NeuroLogosTricameral` (line 2515) - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2550) - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `preprocess_and_cache_spectrograms` (line 49) - *Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt
Esto elimina el cuello de botella de I/O durante entrenamiento*
- `apply_emergency_fixes` (line 120)
- `setup_flickr8k_with_audio` (line 142) - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 316) - *Construye vocabulario desde el archivo de captions*
- `forward` (line 1335)
- `compute_alignment_loss` (line 2666) - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2695)
- `train_tricameral` (line 2812)
- `__init__` (line 347)
- `compute_surprise` (line 371) - *FIX: Clamp de cross-entropy para evitar infinitos*
- `calculate_importance` (line 386) - *FIX: Clamp de surprise_score para evitar probabilidades degeneradas*
- `_calculate_novelty` (line 402) - *FIX: Manejo de edge case cuando no hay memorias*
- `store_episode` (line 427)
- `_update_unified_buffer` (line 456) - *FIX: Verificar integridad de scores antes de unificar*
- `sample` (line 470) - *FIX: Manejo de edge cases en sampling probabilístico*
- `_sample_from_buffer` (line 494) - *FIX: Estabilización completa de probabilidades de sampling*
- `apply_forgetting_curve` (line 535)
- `_purge_low_score_memories` (line 545) - *FIX: Purga con threshold ajustado y verificación de scores*
- `__init__` (line 578)
- `assess_reasoning_state` (line 598) - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 642) - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 688) - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 778) - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 812) - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 821) - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 834) - *Jaccard similarity entre palabras*
- `__init__` (line 849)
- `_get_ngrams_cached` (line 863) - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 872)
- `compute_cider` (line 911) - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 925)
- `get_cache_stats` (line 937) - *FIX: Estadísticas de cache actualizadas*
- `sentence_bleu` (line 967)
- `token_accuracy` (line 990)
- `word_overlap` (line 1000)
- `__init__` (line 1009)
- `reason_causally` (line 1036)
- `_predict_interventions` (line 1050)
- `update_knowledge_graph` (line 1067)
- `query_causal_chain` (line 1073)
- `sentence_bleu` (line 1089)
- `token_accuracy` (line 1112)
- `word_overlap` (line 1122)
- `__init__` (line 1136)
- `forward` (line 1184)
- `_calculate_homeostasis_metric` (line 1219) - *Calcula métrica de homeostasis con estabilización numérica*
- `hebbian_update` (line 1229)
- `update_physiology_advanced` (line 1278)
- `__init__` (line 1361)
- `triangulate_signals` (line 1368)
- `count_convergent_signals` (line 1379)
- `diagnose_with_triangulation` (line 1382)
- `apply_triangulated_intervention` (line 1427)
- `_reset_liquid_neuron` (line 1496)
- `__init__` (line 1511)
- `forward` (line 1596)
- `_apply_chain_of_thought` (line 1653)
- `_apply_multi_token_prediction` (line 1694)
- `_apply_structural_attention` (line 1737)
- `_greedy_decode` (line 1759)
- `_get_init_state` (line 1819)
- `__init__` (line 1842)
- `forward` (line 1880)
- `__init__` (line 1909)
- `forward` (line 1947)
- `__init__` (line 1994)
- `_apply_flash_attention` (line 2057) - *Aplica Flash Attention nativa de PyTorch 2.0+
FIX: Corrección de dimensiones para seq_len variable*
- `forward` (line 2090) - *FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal*
- `update_channel_fatigue` (line 2169)
- `adjust_gates_by_fatigue` (line 2190) - *Lógica original de ajuste de gates*
- `__init__` (line 2208)
- `_get_cached_norm` (line 2231) - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 2248) - *Medición de coherencia multimodal con sincronización entre canales*
- `evaluate_reasoning_quality` (line 2305)
- `calculate_synergy` (line 2342)
- `calculate_health` (line 2353)
- `update` (line 2362)
- `get_recent_avg` (line 2379)
- `visualize_fatigue_distribution` (line 2395)
- `visualize_reasoning_metrics` (line 2417)
- `report` (line 2429)
- `__init__` (line 2518)
- `forward` (line 2525)
- `__init__` (line 2553)
- `__len__` (line 2610)
- `__getitem__` (line 2613)

#### `neurologos_tricameral_loss8.0.py`
**Path:** `neurologos_tricameral_loss8.0.py`

**Classs:**
- `HierarchicalEpisodicMemory` (line 342) - *Memoria episódica optimizada con estabilización numérica en sampling
- Fixed: Clamp de surprise scores para evitar probabilidades degeneradas
- Fixed: Verificación explícita de NaN en operaciones de buffer*
- `NeurocognitiveSystem` (line 581)
- `LanguageMetrics` (line 778) - *Métricas de calidad de generación*
- `LinguisticFeedbackLoop` (line 852)
- `CausalReasoningEngine` (line 968)
- `StableLiquidNeuron` (line 1048)
- `TricameralOutput` (line 1235)
- `TriangulatedMedicalSystem` (line 1274)
- `LeftHemisphere` (line 1424)
- `AudioEncoder` (line 1748) - *Encoder de audio optimizado con:
- Pruning estructurado en canales Conv (30% reducción)
- Gradient checkpointing para memoria de activaciones
- Preparación para QAT INT8*
- `RightHemisphereTricameral` (line 1816) - *Hemisferio derecho optimizado:
- Gradient checkpointing obligatorio en ResNet50
- AudioEncoder con canales reducidos (90-180-360)
- Memoria activaciones reducida en 60%*
- `CorpusCallosumTrimodal` (line 1899) - *Corpus Callosum optimizado con:
- Dimensión base reducida: 512→320 dims (-37.5%)
- Bottleneck compartido para 3 canales (1 Linear vs 3 ModuleList)
- Flash Attention / xFormers compatible
- Gates fusionados en tensor único
Reducción: 2.1M → 0.88M parámetros (-58%)*
- `EnhancedDiagnosticsTricameral` (line 2122)
- `NeuroLogosTricameral` (line 2430) - *Arquitectura completa: Visión + Audio -> Lenguaje*
- `Flickr8kMultimodalDataset` (line 2465) - *Dataset que carga imagen, audio del caption y texto desde Kaggle*

**Functions:**
- `preprocess_and_cache_spectrograms` (line 49) - *Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt
Esto elimina el cuello de botella de I/O durante entrenamiento*
- `apply_emergency_fixes` (line 122)
- `setup_flickr8k_with_audio` (line 144) - *Descarga y organiza Flickr8k + Audio del dataset de Kaggle.
Sistema robusto que verifica componentes individuales y descarga solo lo faltante.*
- `build_vocab_flickr` (line 318) - *Construye vocabulario desde el archivo de captions*
- `forward` (line 1249)
- `compute_alignment_loss` (line 2581) - *FIX: Pérdida auxiliar para alineación temprana de canales multimodales
Solo activa en épocas iniciales (epoch < 6)*
- `compute_tricameral_loss` (line 2610)
- `train_tricameral` (line 2727)
- `__init__` (line 349)
- `compute_surprise` (line 373) - *FIX: Clamp de cross-entropy para evitar infinitos*
- `calculate_importance` (line 388) - *FIX: Clamp de surprise_score para evitar probabilidades degeneradas*
- `_calculate_novelty` (line 404) - *FIX: Manejo de edge case cuando no hay memorias*
- `store_episode` (line 429)
- `_update_unified_buffer` (line 460) - *FIX: Verificar integridad de scores antes de unificar*
- `sample` (line 474) - *FIX: Manejo de edge cases en sampling probabilístico*
- `_sample_from_buffer` (line 498) - *FIX: Estabilización completa de probabilidades de sampling*
- `apply_forgetting_curve` (line 539)
- `_purge_low_score_memories` (line 549) - *FIX: Purga con threshold ajustado y verificación de scores*
- `__init__` (line 582)
- `assess_reasoning_state` (line 602) - *Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)*
- `assess_cognitive_state` (line 646) - *Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)*
- `apply_cognitive_intervention` (line 692) - *Aplica intervenciones basadas en estado lingüístico y de razonamiento*
- `sentence_bleu` (line 782) - *BLEU simplificado a nivel de oración*
- `_get_ngrams` (line 816) - *Extraer n-gramas de una lista de tokens*
- `token_accuracy` (line 825) - *Porcentaje de tokens correctos en posición*
- `word_overlap` (line 838) - *Jaccard similarity entre palabras*
- `__init__` (line 853)
- `_get_ngrams_cached` (line 867) - *FIX: Método estático con lru_cache para n-gramas*
- `compute_linguistic_reward` (line 876)
- `compute_cider` (line 915) - *FIX: Uso correcto del cache estático*
- `compute_spice` (line 929)
- `get_cache_stats` (line 941) - *FIX: Estadísticas de cache actualizadas*
- `__init__` (line 969)
- `reason_causally` (line 996)
- `_predict_interventions` (line 1010)
- `update_knowledge_graph` (line 1027)
- `query_causal_chain` (line 1033)
- `__init__` (line 1050)
- `forward` (line 1098)
- `_calculate_homeostasis_metric` (line 1133) - *Calcula métrica de homeostasis con estabilización numérica*
- `hebbian_update` (line 1143)
- `update_physiology_advanced` (line 1192)
- `__init__` (line 1275)
- `triangulate_signals` (line 1282)
- `count_convergent_signals` (line 1293)
- `diagnose_with_triangulation` (line 1296)
- `apply_triangulated_intervention` (line 1341)
- `_reset_liquid_neuron` (line 1410)
- `__init__` (line 1425)
- `forward` (line 1512)
- `_apply_chain_of_thought` (line 1567)
- `_apply_multi_token_prediction` (line 1608)
- `_apply_structural_attention` (line 1652)
- `_greedy_decode` (line 1674)
- `_get_init_state` (line 1734)
- `__init__` (line 1757)
- `forward` (line 1795)
- `__init__` (line 1824)
- `forward` (line 1862)
- `__init__` (line 1909)
- `_apply_flash_attention` (line 1972) - *Aplica Flash Attention nativa de PyTorch 2.0+
FIX: Corrección de dimensiones para seq_len variable*
- `forward` (line 2005) - *FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal*
- `update_channel_fatigue` (line 2084)
- `adjust_gates_by_fatigue` (line 2105) - *Lógica original de ajuste de gates*
- `__init__` (line 2123)
- `_get_cached_norm` (line 2146) - *Cache de normalización con limpieza periódica*
- `measure_callosal_flow` (line 2163) - *Medición de coherencia multimodal con sincronización entre canales*
- `evaluate_reasoning_quality` (line 2220)
- `calculate_synergy` (line 2257)
- `calculate_health` (line 2268)
- `update` (line 2277)
- `get_recent_avg` (line 2294)
- `visualize_fatigue_distribution` (line 2310)
- `visualize_reasoning_metrics` (line 2332)
- `report` (line 2344)
- `__init__` (line 2433)
- `forward` (line 2440)
- `__init__` (line 2468)
- `__len__` (line 2525)
- `__getitem__` (line 2528)

### SH (1 files)

#### `install.sh`
**Path:** `install.sh`

*No symbols extracted*
