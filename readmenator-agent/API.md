# API

## neurologos_tricameral_loss2.7.py

### setup_flickr8k_with_audio `def setup_flickr8k_with_audio(data_dir)`
- Defined: `neurologos_tricameral_loss2.7.py:53`
- Doc: Descarga y organiza Flickr8k + Audio del dataset de Kaggle.

### build_vocab_flickr `def build_vocab_flickr(captions_file, vocab_size)`
- Defined: `neurologos_tricameral_loss2.7.py:241`
- Doc: Construye vocabulario desde el archivo de captions

### compute_alignment_loss `def compute_alignment_loss(visual_features, channels, alpha, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:2354`
- Doc: FIX: Pérdida auxiliar para alineación temprana de canales multimodales

### compute_tricameral_loss `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, lambda_reward, lambda_mtp)`
- Defined: `neurologos_tricameral_loss2.7.py:2382`

### train_tricameral `def train_tricameral()`
- Defined: `neurologos_tricameral_loss2.7.py:2429`

### __init__ `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- Defined: `neurologos_tricameral_loss2.7.py:266`

### compute_surprise `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- Defined: `neurologos_tricameral_loss2.7.py:292`

### calculate_importance `def calculate_importance(self, episode, surprise_score)`
- Defined: `neurologos_tricameral_loss2.7.py:302`

### _calculate_novelty `def _calculate_novelty(self, episode)`
- Defined: `neurologos_tricameral_loss2.7.py:314`

### store_episode `def store_episode(self, image, audio, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss2.7.py:335`

### _update_unified_buffer `def _update_unified_buffer(self)`
- Defined: `neurologos_tricameral_loss2.7.py:373`

### add `def add(self, image, audio, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss2.7.py:385`

### apply_forgetting_curve `def apply_forgetting_curve(self)`
- Defined: `neurologos_tricameral_loss2.7.py:388`

### _purge_low_score_memories `def _purge_low_score_memories(self)`
- Defined: `neurologos_tricameral_loss2.7.py:404`

### sample `def sample(self, batch_size, memory_level)`
- Defined: `neurologos_tricameral_loss2.7.py:430`

### _sample_from_buffer `def _sample_from_buffer(self, buffer, scores, batch_size)`
- Defined: `neurologos_tricameral_loss2.7.py:460`

### get_total_size `def get_total_size(self)`
- Defined: `neurologos_tricameral_loss2.7.py:488`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss2.7.py:497`

### assess_reasoning_state `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:517`
- Doc: Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)

### assess_cognitive_state `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:561`
- Doc: Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)

### apply_cognitive_intervention `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)`
- Defined: `neurologos_tricameral_loss2.7.py:607`
- Doc: Aplica intervenciones basadas en estado lingüístico y de razonamiento

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss2.7.py:697`
- Doc: BLEU simplificado a nivel de oración

### _get_ngrams `def _get_ngrams(tokens, n)`
- Defined: `neurologos_tricameral_loss2.7.py:731`
- Doc: Extraer n-gramas de una lista de tokens

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:740`
- Doc: Porcentaje de tokens correctos en posición

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:753`
- Doc: Jaccard similarity entre palabras

### __init__ `def __init__(self, alpha, beta)`
- Defined: `neurologos_tricameral_loss2.7.py:768`

### _get_ngrams_cached `def _get_ngrams_cached(sentence, n)`
- Defined: `neurologos_tricameral_loss2.7.py:782`
- Doc: FIX: Método estático con lru_cache para n-gramas

### compute_linguistic_reward `def compute_linguistic_reward(self, references, hypotheses)`
- Defined: `neurologos_tricameral_loss2.7.py:791`

### compute_cider `def compute_cider(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:830`
- Doc: FIX: Uso correcto del cache estático

### compute_spice `def compute_spice(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:844`

### get_cache_stats `def get_cache_stats(self)`
- Defined: `neurologos_tricameral_loss2.7.py:856`
- Doc: FIX: Estadísticas de cache actualizadas

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss2.7.py:886`

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:909`

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:919`

### __init__ `def __init__(self, hidden_dim)`
- Defined: `neurologos_tricameral_loss2.7.py:928`

### reason_causally `def reason_causally(self, observation, context)`
- Defined: `neurologos_tricameral_loss2.7.py:955`

### _predict_interventions `def _predict_interventions(self, hypothesis, confidence)`
- Defined: `neurologos_tricameral_loss2.7.py:969`

### update_knowledge_graph `def update_knowledge_graph(self, cause, effect, strength)`
- Defined: `neurologos_tricameral_loss2.7.py:986`

### query_causal_chain `def query_causal_chain(self, start_node, end_node)`
- Defined: `neurologos_tricameral_loss2.7.py:992`

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss2.7.py:1008`

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:1031`

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss2.7.py:1041`

### __init__ `def __init__(self, in_dim, out_dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1054`

### forward `def forward(self, x)`
- Defined: `neurologos_tricameral_loss2.7.py:1096`

### _calculate_homeostasis_metric `def _calculate_homeostasis_metric(self, output)`
- Defined: `neurologos_tricameral_loss2.7.py:1112`
- Doc: Calcula métrica de homeostasis basada en la estabilidad del output

### hebbian_update `def hebbian_update(self, post, pre, plasticity)`
- Defined: `neurologos_tricameral_loss2.7.py:1121`

### update_physiology_advanced `def update_physiology_advanced(self, loss_value)`
- Defined: `neurologos_tricameral_loss2.7.py:1159`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss2.7.py:1193`

### triangulate_signals `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss2.7.py:1200`

### count_convergent_signals `def count_convergent_signals(self, signals, pattern)`
- Defined: `neurologos_tricameral_loss2.7.py:1211`

### diagnose_with_triangulation `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:1214`

### apply_triangulated_intervention `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:1259`

### _reset_liquid_neuron `def _reset_liquid_neuron(self, liquid_neuron)`
- Defined: `neurologos_tricameral_loss2.7.py:1328`
- Doc: Reset completo de una neurona líquida

### __init__ `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1344`

### forward `def forward(self, visual_context, captions, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:1426`

### _apply_chain_of_thought `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- Defined: `neurologos_tricameral_loss2.7.py:1473`

### _greedy_decode `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:1513`

### _apply_multi_token_prediction `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- Defined: `neurologos_tricameral_loss2.7.py:1574`

### _apply_structural_attention `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- Defined: `neurologos_tricameral_loss2.7.py:1616`

### _get_init_state `def _get_init_state(self, visual_context)`
- Defined: `neurologos_tricameral_loss2.7.py:1637`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1655`

### forward `def forward(self, mel_spec)`
- Defined: `neurologos_tricameral_loss2.7.py:1689`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1705`

### forward `def forward(self, image, audio)`
- Defined: `neurologos_tricameral_loss2.7.py:1745`
- Doc: Args:

### __init__ `def __init__(self, dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1787`

### forward `def forward(self, right_features)`
- Defined: `neurologos_tricameral_loss2.7.py:1835`

### update_channel_fatigue `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- Defined: `neurologos_tricameral_loss2.7.py:1896`

### adjust_gates_by_fatigue `def adjust_gates_by_fatigue(self)`
- Defined: `neurologos_tricameral_loss2.7.py:1918`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss2.7.py:1940`

### _get_cached_norm `def _get_cached_norm(self, tensor, dim)`
- Defined: `neurologos_tricameral_loss2.7.py:1962`
- Doc: Cache de normalización con limpieza periódica

### measure_callosal_flow `def measure_callosal_flow(self, right_features, left_context, channels)`
- Defined: `neurologos_tricameral_loss2.7.py:1980`

### evaluate_reasoning_quality `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- Defined: `neurologos_tricameral_loss2.7.py:2010`

### calculate_synergy `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- Defined: `neurologos_tricameral_loss2.7.py:2047`

### calculate_health `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- Defined: `neurologos_tricameral_loss2.7.py:2058`

### update `def update(self)`
- Defined: `neurologos_tricameral_loss2.7.py:2067`

### get_recent_avg `def get_recent_avg(self, key, n)`
- Defined: `neurologos_tricameral_loss2.7.py:2084`

### visualize_fatigue_distribution `def visualize_fatigue_distribution(self, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:2100`

### visualize_reasoning_metrics `def visualize_reasoning_metrics(self, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:2124`

### report `def report(self, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:2136`

### __init__ `def __init__(self, vocab_size)`
- Defined: `neurologos_tricameral_loss2.7.py:2218`

### forward `def forward(self, image, audio, captions, epoch)`
- Defined: `neurologos_tricameral_loss2.7.py:2224`

### __init__ `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate)`
- Defined: `neurologos_tricameral_loss2.7.py:2253`

### __len__ `def __len__(self)`
- Defined: `neurologos_tricameral_loss2.7.py:2301`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `neurologos_tricameral_loss2.7.py:2305`

## neurologos_tricameral_loss3.9.py

### compute_loss `def compute_loss(logits, captions, gate, vocab, linguistic_reward, lambda_reward)`
- Defined: `neurologos_tricameral_loss3.9.py:20`
- Doc: Función de pérdida extendida que incorpora recompensa lingüística

### build_vocab_flickr `def build_vocab_flickr(captions_file, vocab_size)`
- Defined: `neurologos_tricameral_loss3.9.py:1745`

### setup_flickr8k `def setup_flickr8k(data_dir)`
- Defined: `neurologos_tricameral_loss3.9.py:1763`

### compute_alignment_loss `def compute_alignment_loss(visual_features, channels, alpha)`
- Defined: `neurologos_tricameral_loss3.9.py:1834`
- Doc: Pérdida auxiliar para forzar alineación entre características visuales

### train_with_metrics `def train_with_metrics()`
- Defined: `neurologos_tricameral_loss3.9.py:1858`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss3.9.py:55`

### assess_cognitive_state `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:76`
- Doc: Evalúa el estado cognitivo del modelo basándose en métricas lingüísticas

### evaluate_gate_state `def evaluate_gate_state(self, gate_value, current_metrics)`
- Defined: `neurologos_tricameral_loss3.9.py:124`
- Doc: MEJORA: Evaluar estado del gate con sistema inmune

### update_trauma_memory `def update_trauma_memory(self, gate_value, metrics, outcome)`
- Defined: `neurologos_tricameral_loss3.9.py:142`
- Doc: MEJORA: Actualizar memoria traumática basada en resultados

### apply_stochastic_perturbation `def apply_stochastic_perturbation(self, model, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:155`
- Doc: MEJORA: Aplicar micro-perturbaciones estocásticas

### apply_cognitive_intervention `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)`
- Defined: `neurologos_tricameral_loss3.9.py:171`
- Doc: Aplica intervenciones cognitivas basadas en el estado lingüístico

### __init__ `def __init__(self, alpha, beta)`
- Defined: `neurologos_tricameral_loss3.9.py:331`

### compute_linguistic_reward `def compute_linguistic_reward(self, references, hypotheses)`
- Defined: `neurologos_tricameral_loss3.9.py:347`
- Doc: Calcula una recompensa combinada basada en CIDEr y SPICE.

### compute_cider `def compute_cider(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss3.9.py:389`
- Doc: Versión simplificada de CIDEr para uso en entrenamiento.

### compute_spice `def compute_spice(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss3.9.py:427`
- Doc: Versión simplificada de SPICE para uso en entrenamiento.

### _get_ngrams `def _get_ngrams(self, sentence, n)`
- Defined: `neurologos_tricameral_loss3.9.py:443`
- Doc: Extrae n-gramas de una oración

### get_cache_stats `def get_cache_stats(self)`
- Defined: `neurologos_tricameral_loss3.9.py:452`
- Doc: Obtiene estadísticas del sistema de caché

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss3.9.py:483`
- Doc: BLEU simplificado a nivel de oración

### _get_ngrams `def _get_ngrams(tokens, n)`
- Defined: `neurologos_tricameral_loss3.9.py:517`
- Doc: Extraer n-gramas de una lista de tokens

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss3.9.py:526`
- Doc: Porcentaje de tokens correctos en posición

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss3.9.py:539`
- Doc: Jaccard similarity entre palabras

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss3.9.py:555`

### triangulate_signals `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss3.9.py:560`
- Doc: Identificar señales convergentes que confirman problemas

### count_convergent_signals `def count_convergent_signals(self, signals, pattern)`
- Defined: `neurologos_tricameral_loss3.9.py:592`
- Doc: Contar cuántas señales del patrón están activas

### diagnose_with_triangulation `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss3.9.py:596`
- Doc: Diagnosticar SOLO con confirmación múltiple

### apply_triangulated_intervention `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:659`
- Doc: Aplicar intervención SOLO si confianza es alta

### __init__ `def __init__(self, in_dim, out_dim)`
- Defined: `neurologos_tricameral_loss3.9.py:828`

### forward `def forward(self, x)`
- Defined: `neurologos_tricameral_loss3.9.py:871`

### hebbian_update `def hebbian_update(self, post, pre, plasticity)`
- Defined: `neurologos_tricameral_loss3.9.py:893`

### update_physiology_advanced `def update_physiology_advanced(self, loss_value)`
- Defined: `neurologos_tricameral_loss3.9.py:932`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss3.9.py:974`

### forward `def forward(self, image)`
- Defined: `neurologos_tricameral_loss3.9.py:982`

### __init__ `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- Defined: `neurologos_tricameral_loss3.9.py:989`

### beam_search_decode `def beam_search_decode(self, visual_context, channels, beam_width, max_len, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:1066`

### forward `def forward(self, visual_context, captions, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:1147`

### _apply_structural_attention `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- Defined: `neurologos_tricameral_loss3.9.py:1185`
- Doc: Aplica atención específica para cada canal estructural (objetos, acciones, escena).

### _get_init_state `def _get_init_state(self, visual_context)`
- Defined: `neurologos_tricameral_loss3.9.py:1230`

### __init__ `def __init__(self, dim)`
- Defined: `neurologos_tricameral_loss3.9.py:1245`

### forward `def forward(self, right_features, left_features)`
- Defined: `neurologos_tricameral_loss3.9.py:1308`

### update_channel_fatigue `def update_channel_fatigue(self, objects_channel, actions_channel, scene_channel)`
- Defined: `neurologos_tricameral_loss3.9.py:1381`
- Doc: MEJORA: Actualizar fatiga específica por canal

### adjust_gates_by_fatigue `def adjust_gates_by_fatigue(self)`
- Defined: `neurologos_tricameral_loss3.9.py:1404`
- Doc: MEJORA: Ajustar gates basado en fatiga de cada canal

### __init__ `def __init__(self, vocab_size)`
- Defined: `neurologos_tricameral_loss3.9.py:1421`

### forward `def forward(self, image, captions, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:1427`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss3.9.py:1447`

### measure_callosal_flow `def measure_callosal_flow(self, right_features, left_context, channels)`
- Defined: `neurologos_tricameral_loss3.9.py:1460`

### calculate_synergy `def calculate_synergy(self, right_node, callosal_flow, left_gate_mean, left_gate_std)`
- Defined: `neurologos_tricameral_loss3.9.py:1490`

### calculate_health `def calculate_health(self, right_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- Defined: `neurologos_tricameral_loss3.9.py:1499`

### update `def update(self)`
- Defined: `neurologos_tricameral_loss3.9.py:1508`

### get_recent_avg `def get_recent_avg(self, key, n)`
- Defined: `neurologos_tricameral_loss3.9.py:1519`

### visualize_fatigue_distribution `def visualize_fatigue_distribution(self, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:1538`
- Doc: MEJORA: Visualizar distribución de fatiga entre canales

### report `def report(self, epoch)`
- Defined: `neurologos_tricameral_loss3.9.py:1567`

### __init__ `def __init__(self, capacity, surprise_threshold)`
- Defined: `neurologos_tricameral_loss3.9.py:1662`

### compute_surprise `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- Defined: `neurologos_tricameral_loss3.9.py:1668`

### add `def add(self, image, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss3.9.py:1679`

### sample `def sample(self, batch_size)`
- Defined: `neurologos_tricameral_loss3.9.py:1689`

### __init__ `def __init__(self, images_dir, captions_file, vocab, transform, max_len)`
- Defined: `neurologos_tricameral_loss3.9.py:1709`

### __len__ `def __len__(self)`
- Defined: `neurologos_tricameral_loss3.9.py:1726`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `neurologos_tricameral_loss3.9.py:1729`

## neurologos_tricameral_loss4.5.py

### compute_loss `def compute_loss(logits, captions, gate, vocab)`
- Defined: `neurologos_tricameral_loss4.5.py:20`

### build_vocab_flickr `def build_vocab_flickr(captions_file, vocab_size)`
- Defined: `neurologos_tricameral_loss4.5.py:991`

### setup_flickr8k `def setup_flickr8k(data_dir)`
- Defined: `neurologos_tricameral_loss4.5.py:1009`

### train_with_metrics `def train_with_metrics()`
- Defined: `neurologos_tricameral_loss4.5.py:1081`

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss4.5.py:48`
- Doc: BLEU simplificado a nivel de oración

### _get_ngrams `def _get_ngrams(tokens, n)`
- Defined: `neurologos_tricameral_loss4.5.py:82`
- Doc: Extraer n-gramas de una lista de tokens

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss4.5.py:91`
- Doc: Porcentaje de tokens correctos en posición

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss4.5.py:104`
- Doc: Jaccard similarity entre palabras

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss4.5.py:120`

### triangulate_signals `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss4.5.py:125`
- Doc: Identificar señales convergentes que confirman problemas

### count_convergent_signals `def count_convergent_signals(self, signals, pattern)`
- Defined: `neurologos_tricameral_loss4.5.py:157`
- Doc: Contar cuántas señales del patrón están activas

### diagnose_with_triangulation `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss4.5.py:161`
- Doc: Diagnosticar SOLO con confirmación múltiple

### apply_triangulated_intervention `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- Defined: `neurologos_tricameral_loss4.5.py:224`
- Doc: Aplicar intervención SOLO si confianza es alta

### __init__ `def __init__(self, in_dim, out_dim)`
- Defined: `neurologos_tricameral_loss4.5.py:393`

### forward `def forward(self, x)`
- Defined: `neurologos_tricameral_loss4.5.py:431`

### hebbian_update `def hebbian_update(self, post, pre, plasticity)`
- Defined: `neurologos_tricameral_loss4.5.py:453`

### update_physiology_advanced `def update_physiology_advanced(self, loss_value)`
- Defined: `neurologos_tricameral_loss4.5.py:492`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss4.5.py:519`

### forward `def forward(self, image)`
- Defined: `neurologos_tricameral_loss4.5.py:527`

### __init__ `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- Defined: `neurologos_tricameral_loss4.5.py:534`

### beam_search_decode `def beam_search_decode(self, visual_context, beam_width, max_len, epoch)`
- Defined: `neurologos_tricameral_loss4.5.py:584`

### forward `def forward(self, visual_context, captions, max_len, epoch)`
- Defined: `neurologos_tricameral_loss4.5.py:657`

### _get_init_state `def _get_init_state(self, visual_context)`
- Defined: `neurologos_tricameral_loss4.5.py:695`

### __init__ `def __init__(self, dim)`
- Defined: `neurologos_tricameral_loss4.5.py:710`

### forward `def forward(self, right_features)`
- Defined: `neurologos_tricameral_loss4.5.py:742`

### __init__ `def __init__(self, vocab_size)`
- Defined: `neurologos_tricameral_loss4.5.py:766`

### forward `def forward(self, image, captions, epoch)`
- Defined: `neurologos_tricameral_loss4.5.py:772`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss4.5.py:787`

### measure_callosal_flow `def measure_callosal_flow(self, right_features, left_context)`
- Defined: `neurologos_tricameral_loss4.5.py:797`

### calculate_synergy `def calculate_synergy(self, right_node, callosal_flow, left_gate_mean, left_gate_std)`
- Defined: `neurologos_tricameral_loss4.5.py:806`

### calculate_health `def calculate_health(self, right_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- Defined: `neurologos_tricameral_loss4.5.py:815`

### update `def update(self)`
- Defined: `neurologos_tricameral_loss4.5.py:824`

### get_recent_avg `def get_recent_avg(self, key, n)`
- Defined: `neurologos_tricameral_loss4.5.py:829`

### report `def report(self, epoch)`
- Defined: `neurologos_tricameral_loss4.5.py:834`

### __init__ `def __init__(self, capacity, surprise_threshold)`
- Defined: `neurologos_tricameral_loss4.5.py:908`

### compute_surprise `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- Defined: `neurologos_tricameral_loss4.5.py:914`

### add `def add(self, image, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss4.5.py:925`

### sample `def sample(self, batch_size)`
- Defined: `neurologos_tricameral_loss4.5.py:935`

### __init__ `def __init__(self, images_dir, captions_file, vocab, transform, max_len)`
- Defined: `neurologos_tricameral_loss4.5.py:955`

### __len__ `def __len__(self)`
- Defined: `neurologos_tricameral_loss4.5.py:972`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `neurologos_tricameral_loss4.5.py:975`

## neurologos_tricameral_loss5.4.py

### preprocess_and_cache_spectrograms `def preprocess_and_cache_spectrograms(audio_dir, cache_dir, sample_rate, target_len)`
- Defined: `neurologos_tricameral_loss5.4.py:49`
- Doc: Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt

### apply_emergency_fixes `def apply_emergency_fixes(model)`
- Defined: `neurologos_tricameral_loss5.4.py:120`

### setup_flickr8k_with_audio `def setup_flickr8k_with_audio(data_dir)`
- Defined: `neurologos_tricameral_loss5.4.py:142`
- Doc: Descarga y organiza Flickr8k + Audio del dataset de Kaggle.

### build_vocab_flickr `def build_vocab_flickr(captions_file, vocab_size)`
- Defined: `neurologos_tricameral_loss5.4.py:316`
- Doc: Construye vocabulario desde el archivo de captions

### forward `def forward(self, image, audio, captions, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:1335`

### compute_alignment_loss `def compute_alignment_loss(visual_features, channels, alpha, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:2666`
- Doc: FIX: Pérdida auxiliar para alineación temprana de canales multimodales

### compute_tricameral_loss `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, channels, epoch, lambda_reward, lambda_mtp)`
- Defined: `neurologos_tricameral_loss5.4.py:2695`

### train_tricameral `def train_tricameral()`
- Defined: `neurologos_tricameral_loss5.4.py:2812`

### __init__ `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- Defined: `neurologos_tricameral_loss5.4.py:347`

### compute_surprise `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- Defined: `neurologos_tricameral_loss5.4.py:371`
- Doc: FIX: Clamp de cross-entropy para evitar infinitos

### calculate_importance `def calculate_importance(self, episode, surprise_score)`
- Defined: `neurologos_tricameral_loss5.4.py:386`
- Doc: FIX: Clamp de surprise_score para evitar probabilidades degeneradas

### _calculate_novelty `def _calculate_novelty(self, episode)`
- Defined: `neurologos_tricameral_loss5.4.py:402`
- Doc: FIX: Manejo de edge case cuando no hay memorias

### store_episode `def store_episode(self, image, audio, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss5.4.py:427`

### _update_unified_buffer `def _update_unified_buffer(self)`
- Defined: `neurologos_tricameral_loss5.4.py:456`
- Doc: FIX: Verificar integridad de scores antes de unificar

### sample `def sample(self, batch_size, memory_level)`
- Defined: `neurologos_tricameral_loss5.4.py:470`
- Doc: FIX: Manejo de edge cases en sampling probabilístico

### _sample_from_buffer `def _sample_from_buffer(self, buffer, scores, batch_size)`
- Defined: `neurologos_tricameral_loss5.4.py:494`
- Doc: FIX: Estabilización completa de probabilidades de sampling

### apply_forgetting_curve `def apply_forgetting_curve(self)`
- Defined: `neurologos_tricameral_loss5.4.py:535`

### _purge_low_score_memories `def _purge_low_score_memories(self)`
- Defined: `neurologos_tricameral_loss5.4.py:545`
- Doc: FIX: Purga con threshold ajustado y verificación de scores

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss5.4.py:578`

### assess_reasoning_state `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:598`
- Doc: Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)

### assess_cognitive_state `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:642`
- Doc: Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)

### apply_cognitive_intervention `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)`
- Defined: `neurologos_tricameral_loss5.4.py:688`
- Doc: Aplica intervenciones basadas en estado lingüístico y de razonamiento

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss5.4.py:778`
- Doc: BLEU simplificado a nivel de oración

### _get_ngrams `def _get_ngrams(tokens, n)`
- Defined: `neurologos_tricameral_loss5.4.py:812`
- Doc: Extraer n-gramas de una lista de tokens

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:821`
- Doc: Porcentaje de tokens correctos en posición

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:834`
- Doc: Jaccard similarity entre palabras

### __init__ `def __init__(self, alpha, beta)`
- Defined: `neurologos_tricameral_loss5.4.py:849`

### _get_ngrams_cached `def _get_ngrams_cached(sentence, n)`
- Defined: `neurologos_tricameral_loss5.4.py:863`
- Doc: FIX: Método estático con lru_cache para n-gramas

### compute_linguistic_reward `def compute_linguistic_reward(self, references, hypotheses)`
- Defined: `neurologos_tricameral_loss5.4.py:872`

### compute_cider `def compute_cider(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:911`
- Doc: FIX: Uso correcto del cache estático

### compute_spice `def compute_spice(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:925`

### get_cache_stats `def get_cache_stats(self)`
- Defined: `neurologos_tricameral_loss5.4.py:937`
- Doc: FIX: Estadísticas de cache actualizadas

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss5.4.py:967`

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:990`

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:1000`

### __init__ `def __init__(self, hidden_dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1009`

### reason_causally `def reason_causally(self, observation, context)`
- Defined: `neurologos_tricameral_loss5.4.py:1036`

### _predict_interventions `def _predict_interventions(self, hypothesis, confidence)`
- Defined: `neurologos_tricameral_loss5.4.py:1050`

### update_knowledge_graph `def update_knowledge_graph(self, cause, effect, strength)`
- Defined: `neurologos_tricameral_loss5.4.py:1067`

### query_causal_chain `def query_causal_chain(self, start_node, end_node)`
- Defined: `neurologos_tricameral_loss5.4.py:1073`

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss5.4.py:1089`

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:1112`

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss5.4.py:1122`

### __init__ `def __init__(self, in_dim, out_dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1136`

### forward `def forward(self, x)`
- Defined: `neurologos_tricameral_loss5.4.py:1184`

### _calculate_homeostasis_metric `def _calculate_homeostasis_metric(self, output)`
- Defined: `neurologos_tricameral_loss5.4.py:1219`
- Doc: Calcula métrica de homeostasis con estabilización numérica

### hebbian_update `def hebbian_update(self, post, pre, plasticity)`
- Defined: `neurologos_tricameral_loss5.4.py:1229`

### update_physiology_advanced `def update_physiology_advanced(self, loss_value)`
- Defined: `neurologos_tricameral_loss5.4.py:1278`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss5.4.py:1361`

### triangulate_signals `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss5.4.py:1368`

### count_convergent_signals `def count_convergent_signals(self, signals, pattern)`
- Defined: `neurologos_tricameral_loss5.4.py:1379`

### diagnose_with_triangulation `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:1382`

### apply_triangulated_intervention `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:1427`

### _reset_liquid_neuron `def _reset_liquid_neuron(self, liquid_neuron)`
- Defined: `neurologos_tricameral_loss5.4.py:1496`

### __init__ `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1511`

### forward `def forward(self, visual_context, captions, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:1596`

### _apply_chain_of_thought `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- Defined: `neurologos_tricameral_loss5.4.py:1653`

### _apply_multi_token_prediction `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- Defined: `neurologos_tricameral_loss5.4.py:1694`

### _apply_structural_attention `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- Defined: `neurologos_tricameral_loss5.4.py:1737`

### _greedy_decode `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:1759`

### _get_init_state `def _get_init_state(self, visual_context)`
- Defined: `neurologos_tricameral_loss5.4.py:1819`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1842`

### forward `def forward(self, mel_spec)`
- Defined: `neurologos_tricameral_loss5.4.py:1880`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1909`

### forward `def forward(self, image, audio)`
- Defined: `neurologos_tricameral_loss5.4.py:1947`

### __init__ `def __init__(self, dim)`
- Defined: `neurologos_tricameral_loss5.4.py:1994`

### _apply_flash_attention `def _apply_flash_attention(self, x)`
- Defined: `neurologos_tricameral_loss5.4.py:2057`
- Doc: Aplica Flash Attention nativa de PyTorch 2.0+

### forward `def forward(self, right_features)`
- Defined: `neurologos_tricameral_loss5.4.py:2090`
- Doc: FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal

### update_channel_fatigue `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- Defined: `neurologos_tricameral_loss5.4.py:2169`

### adjust_gates_by_fatigue `def adjust_gates_by_fatigue(self)`
- Defined: `neurologos_tricameral_loss5.4.py:2190`
- Doc: Lógica original de ajuste de gates

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss5.4.py:2208`

### _get_cached_norm `def _get_cached_norm(self, tensor, dim)`
- Defined: `neurologos_tricameral_loss5.4.py:2231`
- Doc: Cache de normalización con limpieza periódica

### measure_callosal_flow `def measure_callosal_flow(self, right_features, left_context, channels)`
- Defined: `neurologos_tricameral_loss5.4.py:2248`
- Doc: Medición de coherencia multimodal con sincronización entre canales

### evaluate_reasoning_quality `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- Defined: `neurologos_tricameral_loss5.4.py:2305`

### calculate_synergy `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- Defined: `neurologos_tricameral_loss5.4.py:2342`

### calculate_health `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- Defined: `neurologos_tricameral_loss5.4.py:2353`

### update `def update(self)`
- Defined: `neurologos_tricameral_loss5.4.py:2362`

### get_recent_avg `def get_recent_avg(self, key, n)`
- Defined: `neurologos_tricameral_loss5.4.py:2379`

### visualize_fatigue_distribution `def visualize_fatigue_distribution(self, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:2395`

### visualize_reasoning_metrics `def visualize_reasoning_metrics(self, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:2417`

### report `def report(self, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:2429`

### __init__ `def __init__(self, vocab_size)`
- Defined: `neurologos_tricameral_loss5.4.py:2518`

### forward `def forward(self, image, audio, captions, epoch)`
- Defined: `neurologos_tricameral_loss5.4.py:2525`

### __init__ `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate, use_cache, cache_dir)`
- Defined: `neurologos_tricameral_loss5.4.py:2553`

### __len__ `def __len__(self)`
- Defined: `neurologos_tricameral_loss5.4.py:2610`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `neurologos_tricameral_loss5.4.py:2613`

## neurologos_tricameral_loss8.0.py

### preprocess_and_cache_spectrograms `def preprocess_and_cache_spectrograms(audio_dir, cache_dir, sample_rate, target_len)`
- Defined: `neurologos_tricameral_loss8.0.py:49`
- Doc: Preprocesa todos los archivos .wav a Mel-spectrogramas y los guarda como tensores .pt

### apply_emergency_fixes `def apply_emergency_fixes(model)`
- Defined: `neurologos_tricameral_loss8.0.py:122`

### setup_flickr8k_with_audio `def setup_flickr8k_with_audio(data_dir)`
- Defined: `neurologos_tricameral_loss8.0.py:144`
- Doc: Descarga y organiza Flickr8k + Audio del dataset de Kaggle.

### build_vocab_flickr `def build_vocab_flickr(captions_file, vocab_size)`
- Defined: `neurologos_tricameral_loss8.0.py:318`
- Doc: Construye vocabulario desde el archivo de captions

### forward `def forward(self, image, audio, captions, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:1249`

### compute_alignment_loss `def compute_alignment_loss(visual_features, channels, alpha, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:2581`
- Doc: FIX: Pérdida auxiliar para alineación temprana de canales multimodales

### compute_tricameral_loss `def compute_tricameral_loss(logits, captions, gate, vocab, visual_post, audio_post, mtp_loss, linguistic_reward, channels, epoch, lambda_reward, lambda_mtp)`
- Defined: `neurologos_tricameral_loss8.0.py:2610`

### train_tricameral `def train_tricameral()`
- Defined: `neurologos_tricameral_loss8.0.py:2727`

### __init__ `def __init__(self, working_capacity, short_term_capacity, importance_threshold)`
- Defined: `neurologos_tricameral_loss8.0.py:349`

### compute_surprise `def compute_surprise(self, predicted_logits, ground_truth, gate_mean)`
- Defined: `neurologos_tricameral_loss8.0.py:373`
- Doc: FIX: Clamp de cross-entropy para evitar infinitos

### calculate_importance `def calculate_importance(self, episode, surprise_score)`
- Defined: `neurologos_tricameral_loss8.0.py:388`
- Doc: FIX: Clamp de surprise_score para evitar probabilidades degeneradas

### _calculate_novelty `def _calculate_novelty(self, episode)`
- Defined: `neurologos_tricameral_loss8.0.py:404`
- Doc: FIX: Manejo de edge case cuando no hay memorias

### store_episode `def store_episode(self, image, audio, caption, surprise_score)`
- Defined: `neurologos_tricameral_loss8.0.py:429`

### _update_unified_buffer `def _update_unified_buffer(self)`
- Defined: `neurologos_tricameral_loss8.0.py:460`
- Doc: FIX: Verificar integridad de scores antes de unificar

### sample `def sample(self, batch_size, memory_level)`
- Defined: `neurologos_tricameral_loss8.0.py:474`
- Doc: FIX: Manejo de edge cases en sampling probabilístico

### _sample_from_buffer `def _sample_from_buffer(self, buffer, scores, batch_size)`
- Defined: `neurologos_tricameral_loss8.0.py:498`
- Doc: FIX: Estabilización completa de probabilidades de sampling

### apply_forgetting_curve `def apply_forgetting_curve(self)`
- Defined: `neurologos_tricameral_loss8.0.py:539`

### _purge_low_score_memories `def _purge_low_score_memories(self)`
- Defined: `neurologos_tricameral_loss8.0.py:549`
- Doc: FIX: Purga con threshold ajustado y verificación de scores

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss8.0.py:582`

### assess_reasoning_state `def assess_reasoning_state(self, mtp_loss, reasoning_steps, logical_coherence, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:602`
- Doc: Evalúa estado del sistema de razonamiento (MTP + Chain-of-Thought)

### assess_cognitive_state `def assess_cognitive_state(self, cider_score, spice_score, combined_reward, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:646`
- Doc: Evalúa estado cognitivo lingüístico (planteau, déficits, sobreajuste)

### apply_cognitive_intervention `def apply_cognitive_intervention(self, model, issues, severity, confidence, epoch, diagnostics)`
- Defined: `neurologos_tricameral_loss8.0.py:692`
- Doc: Aplica intervenciones basadas en estado lingüístico y de razonamiento

### sentence_bleu `def sentence_bleu(reference, hypothesis, weights)`
- Defined: `neurologos_tricameral_loss8.0.py:782`
- Doc: BLEU simplificado a nivel de oración

### _get_ngrams `def _get_ngrams(tokens, n)`
- Defined: `neurologos_tricameral_loss8.0.py:816`
- Doc: Extraer n-gramas de una lista de tokens

### token_accuracy `def token_accuracy(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss8.0.py:825`
- Doc: Porcentaje de tokens correctos en posición

### word_overlap `def word_overlap(reference, hypothesis)`
- Defined: `neurologos_tricameral_loss8.0.py:838`
- Doc: Jaccard similarity entre palabras

### __init__ `def __init__(self, alpha, beta)`
- Defined: `neurologos_tricameral_loss8.0.py:853`

### _get_ngrams_cached `def _get_ngrams_cached(sentence, n)`
- Defined: `neurologos_tricameral_loss8.0.py:867`
- Doc: FIX: Método estático con lru_cache para n-gramas

### compute_linguistic_reward `def compute_linguistic_reward(self, references, hypotheses)`
- Defined: `neurologos_tricameral_loss8.0.py:876`

### compute_cider `def compute_cider(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss8.0.py:915`
- Doc: FIX: Uso correcto del cache estático

### compute_spice `def compute_spice(self, reference, hypothesis)`
- Defined: `neurologos_tricameral_loss8.0.py:929`

### get_cache_stats `def get_cache_stats(self)`
- Defined: `neurologos_tricameral_loss8.0.py:941`
- Doc: FIX: Estadísticas de cache actualizadas

### __init__ `def __init__(self, hidden_dim)`
- Defined: `neurologos_tricameral_loss8.0.py:969`

### reason_causally `def reason_causally(self, observation, context)`
- Defined: `neurologos_tricameral_loss8.0.py:996`

### _predict_interventions `def _predict_interventions(self, hypothesis, confidence)`
- Defined: `neurologos_tricameral_loss8.0.py:1010`

### update_knowledge_graph `def update_knowledge_graph(self, cause, effect, strength)`
- Defined: `neurologos_tricameral_loss8.0.py:1027`

### query_causal_chain `def query_causal_chain(self, start_node, end_node)`
- Defined: `neurologos_tricameral_loss8.0.py:1033`

### __init__ `def __init__(self, in_dim, out_dim)`
- Defined: `neurologos_tricameral_loss8.0.py:1050`

### forward `def forward(self, x)`
- Defined: `neurologos_tricameral_loss8.0.py:1098`

### _calculate_homeostasis_metric `def _calculate_homeostasis_metric(self, output)`
- Defined: `neurologos_tricameral_loss8.0.py:1133`
- Doc: Calcula métrica de homeostasis con estabilización numérica

### hebbian_update `def hebbian_update(self, post, pre, plasticity)`
- Defined: `neurologos_tricameral_loss8.0.py:1143`

### update_physiology_advanced `def update_physiology_advanced(self, loss_value)`
- Defined: `neurologos_tricameral_loss8.0.py:1192`

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss8.0.py:1275`

### triangulate_signals `def triangulate_signals(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow)`
- Defined: `neurologos_tricameral_loss8.0.py:1282`

### count_convergent_signals `def count_convergent_signals(self, signals, pattern)`
- Defined: `neurologos_tricameral_loss8.0.py:1293`

### diagnose_with_triangulation `def diagnose_with_triangulation(self, health_score, liquid_norm, gate_mean, gate_std, callosal_flow, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:1296`

### apply_triangulated_intervention `def apply_triangulated_intervention(self, model, issues, severity, confidence, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:1341`

### _reset_liquid_neuron `def _reset_liquid_neuron(self, liquid_neuron)`
- Defined: `neurologos_tricameral_loss8.0.py:1410`

### __init__ `def __init__(self, vocab_size, embed_dim, hidden_dim)`
- Defined: `neurologos_tricameral_loss8.0.py:1425`

### forward `def forward(self, visual_context, captions, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:1512`

### _apply_chain_of_thought `def _apply_chain_of_thought(self, hidden_states, visual_context, use_reasoning)`
- Defined: `neurologos_tricameral_loss8.0.py:1567`

### _apply_multi_token_prediction `def _apply_multi_token_prediction(self, hidden_states, input_ids)`
- Defined: `neurologos_tricameral_loss8.0.py:1608`

### _apply_structural_attention `def _apply_structural_attention(self, lstm_out, channels, visual_context)`
- Defined: `neurologos_tricameral_loss8.0.py:1652`

### _greedy_decode `def _greedy_decode(self, visual_context, channels, max_len, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:1674`

### _get_init_state `def _get_init_state(self, visual_context)`
- Defined: `neurologos_tricameral_loss8.0.py:1734`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss8.0.py:1757`

### forward `def forward(self, mel_spec)`
- Defined: `neurologos_tricameral_loss8.0.py:1795`

### __init__ `def __init__(self, output_dim)`
- Defined: `neurologos_tricameral_loss8.0.py:1824`

### forward `def forward(self, image, audio)`
- Defined: `neurologos_tricameral_loss8.0.py:1862`

### __init__ `def __init__(self, dim)`
- Defined: `neurologos_tricameral_loss8.0.py:1909`

### _apply_flash_attention `def _apply_flash_attention(self, x)`
- Defined: `neurologos_tricameral_loss8.0.py:1972`
- Doc: Aplica Flash Attention nativa de PyTorch 2.0+

### forward `def forward(self, right_features)`
- Defined: `neurologos_tricameral_loss8.0.py:2005`
- Doc: FIX: Manejo robusto de dimensiones y verificación de coherencia trimodal

### update_channel_fatigue `def update_channel_fatigue(self, visual_channel, audio_channel, semantic_channel)`
- Defined: `neurologos_tricameral_loss8.0.py:2084`

### adjust_gates_by_fatigue `def adjust_gates_by_fatigue(self)`
- Defined: `neurologos_tricameral_loss8.0.py:2105`
- Doc: Lógica original de ajuste de gates

### __init__ `def __init__(self)`
- Defined: `neurologos_tricameral_loss8.0.py:2123`

### _get_cached_norm `def _get_cached_norm(self, tensor, dim)`
- Defined: `neurologos_tricameral_loss8.0.py:2146`
- Doc: Cache de normalización con limpieza periódica

### measure_callosal_flow `def measure_callosal_flow(self, right_features, left_context, channels)`
- Defined: `neurologos_tricameral_loss8.0.py:2163`
- Doc: Medición de coherencia multimodal con sincronización entre canales

### evaluate_reasoning_quality `def evaluate_reasoning_quality(self, generated_texts, reference_texts, reasoning_steps)`
- Defined: `neurologos_tricameral_loss8.0.py:2220`

### calculate_synergy `def calculate_synergy(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std)`
- Defined: `neurologos_tricameral_loss8.0.py:2257`

### calculate_health `def calculate_health(self, visual_node, audio_node, callosal_flow, left_gate_mean, left_gate_std, liquid_norm)`
- Defined: `neurologos_tricameral_loss8.0.py:2268`

### update `def update(self)`
- Defined: `neurologos_tricameral_loss8.0.py:2277`

### get_recent_avg `def get_recent_avg(self, key, n)`
- Defined: `neurologos_tricameral_loss8.0.py:2294`

### visualize_fatigue_distribution `def visualize_fatigue_distribution(self, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:2310`

### visualize_reasoning_metrics `def visualize_reasoning_metrics(self, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:2332`

### report `def report(self, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:2344`

### __init__ `def __init__(self, vocab_size)`
- Defined: `neurologos_tricameral_loss8.0.py:2433`

### forward `def forward(self, image, audio, captions, epoch)`
- Defined: `neurologos_tricameral_loss8.0.py:2440`

### __init__ `def __init__(self, images_dir, audio_dir, captions_file, vocab, img_transform, max_len, sample_rate, use_cache, cache_dir)`
- Defined: `neurologos_tricameral_loss8.0.py:2468`

### __len__ `def __len__(self)`
- Defined: `neurologos_tricameral_loss8.0.py:2525`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `neurologos_tricameral_loss8.0.py:2528`
