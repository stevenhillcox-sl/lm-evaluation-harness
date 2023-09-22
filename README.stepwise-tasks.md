```bash
python -m lm_eval.tasks.mmlu._generate_configs \
--base_yaml_path lm_eval/tasks/mmlu/stepwise/_stepwise_template_yaml \
--save_prefix_path lm_eval/tasks/mmlu/stepwise/mmlu \
--cot_prompt_path lm_eval/tasks/mmlu/_cot_prompts.json \
--task_prefix "" \
--alpaca_template \
--stepwise
```