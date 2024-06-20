* Input: 
* Output:
		```
	    "banner": {
	      "images": {
	        "mobile": "string",
	        "tablet": "string",
	        "desktop": "string"
	      },
	      "url": "string"
	    },
	    "faqs": [
	      {
	        "id": 1,
	        "name": "Общие вопросы",
	        "description": "Описание категории вопросов/ответов",
	        "sort": 100,
	        "questions": [
	          {
	            "id": 1,
	            "question": "test question",
	            "answer": "test answer",
	            "sort": 100,
	            "likes": 3,
	            "dislikes": 3,
	            "has_user_reaction": true,
	            "user_reaction_type": "likes"
	          }
	        ]
	      }
	    ]
	    ```
Получает [[Предметная область "Баннеры"|баннер]] для [[Предметная область "FAQ"|FAQ]], получает список FAQ категорий с вопросами, форматирует их, и отдаёт ответ